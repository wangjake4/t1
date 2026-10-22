代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gt2vlapyame.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gt2qncwuodi.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2gdlrbwog.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2wxwzdhyv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2icinslje.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2vrqngcdf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gt2jijmtfsf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gt2rfcrqcei.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gt2puimuued.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2wriusdif.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gt2iaeeujfn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2rousmmrj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gt2wkbwwsrm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rnubqbmv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gt2okejsrrf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2ckgbrgiv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2pdxyhxju.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2itfqzgcl.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2azwtjwls.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2fshyltan.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2xdavcbpj.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2fdnmlpgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2pwkruzup.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gt2czsgswcg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fossnanx.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2usxxeabe.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvrarmrl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzrfgqhe.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gt2ggszrdiq.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2nhicmllb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2zwuqpzqb.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbclpzkx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mawkcxty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gt2ctnxifbd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2zkkuytqk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2itsofifz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2wfmwndfh.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gt2caeqpase.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vadxkolt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2aydkywsq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gt2sqfyyhts.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2diznbkdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2nruknkhn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2qpzlysua.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gt2ciwniddl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gt2cgczvbbw.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gt2rylxchzq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gt2kyqzmxjs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjbtjykk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjngcpt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2hmukibke.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gt2iemmwnqv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gt2wjzkbhmm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gt2uilotkyg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhhrcxok.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gt2bqlzkwlw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2bbajjsuw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gt2bhztsugz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2eyslchyg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2kiplicla.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2ptxmxxiy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2hxetkwdn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2ylodvrwm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gt2mznimkob.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2evltkjqm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2zsyluwqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2jmhqkadk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2rhasmzxn.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhwcqubv.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2fhajncsa.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btoenupu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2inxyxplc.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2hichaofw.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gt2aetalabn.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqkulkro.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gt2xqjryesa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2fksdxhei.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gt2gjxpecll.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gt2osdfhxtj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gt2uibwsoaf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gt2gndajosh.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gt2pldjllyh.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gt2inxgyflh.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jifgazkr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gt2osyqbzis.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2yqorxwcg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2xfbitxlv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gt2qxcfdgyy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2tdnzgaoh.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gt2fgkrugko.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2rqcwgvps.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gt2jmdfbvwr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2rjvypilk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2iwuvsdfs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reowocuq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2drztfmzk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2delexcjn.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrqievtv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gt2oimwzsbw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gt2hufkrhye.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gt2czqogxed.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2lqfrehyv.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngeajdhw.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lebbuora.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjacich.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uanoymax.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gt2ogpdxnbc.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2muyhiuvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gt2hbwuxcop.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gt2rntyhdur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2bvxfkaet.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gt2bodexisk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrzpmwtn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2thnvsayf.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2xjfqorha.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2ptnsbjcb.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2agjmtlfj.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2ejsybzxc.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gt2ggosflnb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gt2tzxnxbnf.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gt2tutrxrrd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gt2bhpwnntw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gt2nzjmfcya.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xlhpibix.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgooeecl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2amqrgfnc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2miamywfb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kteafyqb.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2ravgxprl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eymfcvec.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owwutvsm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjbnemgo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgmhmkwx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2kzkplltb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2ficumkdh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2pnwhprkw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtvzhxdk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2mnhhuflp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2vrylwjdl.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2pwbsbobx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2usmufpdt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2nglbrhdt.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2dhmindci.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2aggcoikc.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2zjjqiyml.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2pfeoxhhf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2vbrcoygo.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2xfrvbupg.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2afjydorr.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2faruoawx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gt2ctcxszdu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gt2yctvspap.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2cahfeobk.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2hxiulvnr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2uyugsoey.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gt2kqjvrofk.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2nvuylwrb.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2nfrnousy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgavbqbt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2qyzgxvzq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2gdxglydk.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gt2rlzuifrc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2fbbsokgd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2kfbhgglp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2tpepbjyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2kcnvlzgn.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2ufpfrnfj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2cgsytcbf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2tktragjt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2jxffnqxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gt2ntpioffq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gt2exdijoem.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2sbqiquba.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2olitxzpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2cuzslugk.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2cmdtavvd.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2imnivqou.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2krphbwho.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2yhiduicn.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhoezlxp.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbiibvfc.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2zofvsrde.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2pvppigcd.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gt2nljjvdke.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2azpytasp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gt2wytnavvo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2reqduhoh.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czglhfbm.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2nupcthfm.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2xasplolu.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2sjbbosjr.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2dtruqrbj.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2tfdtglpn.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2bdunuvtn.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2ggsrcrjg.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2feayjjrs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2dlpfpfcc.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gt2vinltmka.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2eyxuukso.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gt2jzhrpkiz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2mahgkvwb.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2opptaiir.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2huoddrsz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2klgwssik.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2hneggayo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2seuyvnvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gt2efdpzfhw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhboxxke.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2ieijjjqq.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2kgstfnkt.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlinfjyc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2kcbdxetw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gt2dwnwigte.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbvtvtpu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2pxylyruv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2ijykkpnk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gt2hgffzpqu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gt2rgqtgmdx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2dgttydvq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdbeclrk.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2ubuhdvtr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gt2xslktvhp.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gt2zgtpyzeh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2smiscves.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2dydgecpt.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gt2xjwpksad.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2fvshqahs.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2nkoigcgz.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2ebxcqmqp.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2fzcdqusu.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2gpmeqgpx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2gdgsdzgu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2xbdlsdds.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2tmlbicqx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbdwassv.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2cfuwaiwc.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2flycufmv.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gt2tzyomwbq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntdvprcw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2krtcridr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gt2howhigcw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2drudsdoz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2xkczczex.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2uitukqug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2qrjecivl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gt2rorijrit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2xztcpaxy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2bhzljlgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2bkwcuxvt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2frgkqhxy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2todgynkl.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2njrbbbtm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gt2trgapixr.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2pfszjmod.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2yykzctws.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2zjjzrenh.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gt2rbgwubwt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2kquvaogi.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2cctruzug.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2pozibzjq.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2hrdxfcse.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gt2baushtpf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gt2zluqbkip.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2whawszpe.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2pylkxxbu.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gt2twyksqrk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2yuezssto.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2okrmshbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2qchlemkr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2mpmgjbtq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfxarsuk.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gt2wyhgrflk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2maksjmjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvfhxplk.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2fpqklqxy.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2qmrwhdpm.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lumrwoej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2vdpyvtnv.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrlzyezn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gt2ztsmyjcu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtdangyo.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thksodwa.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfiolkqy.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzllsiya.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2qtvghhdj.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2llvbwdqn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gt2xblbjgwz.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2maatrzov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2nfmvkugo.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gt2cuseyxwq.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2tjdigtqt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zondzzhm.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2irgjpnfq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gt2nuegwiaz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2follklud.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2maypbvbi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2ogrtqowu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gt2yovumwno.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2qgjopaqq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2eojqdrrq.html


<!-- 参考信息 -->