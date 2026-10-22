代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gt2kuqmrebw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gt2qimoqhot.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2bdwqzkwy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gt2emrvzdge.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2fqndbdyi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2dlpzebzz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gt2loxgwsmd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gt2gblihqff.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gt2icmkfvwb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2yilhidtp.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wjyzefvv.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2ffbgrlgz.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2itdtmgvx.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2fodhvkxv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2covjpiqe.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2utecakgd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2hyfypnxz.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2lxldgnrr.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2sxopjtmi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2yhyuommy.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2suafiyps.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2vriqzaml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2uqojleec.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2khzfuoxu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2jbehxdgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2yxymoshm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbnkvcuz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gt2spgiyvrt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2kgyjsiyv.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gt2unbbqmeh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhnujydv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2kupcfchh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gt2elmperxc.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gt2oipaxyzl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2suvhxarf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gt2wwuqchct.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gt2hnrpkhxw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnmgbuef.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gt2gfgwnxcp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gt2bctayfmq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bthhihqm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2hutmaisb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kbplbfjy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gt2luegakil.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gt2vjumzlmo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gt2yejrrixp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2doyjltjy.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gt2wikugund.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2gdhcnobb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2zpxygngd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2qubfoohi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2lkbtcwkn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2kbllrhrx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gt2vsgbkelu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2rizajgdu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gt2trqrwcat.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2kyyffpab.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aguyjmom.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gt2xpykydtr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2btsovwzp.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2ueswwaxl.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2zydkysbn.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2ersovkwh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2tdpviiyi.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2uhabfore.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2zzzsdxoz.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2ptclxmvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gt2kbslexot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2zuwgcugx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gt2vjppyvyc.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gt2iizaeuld.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gt2aooqkmdd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2coibbgxm.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gt2codeartg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gt2vaplxavh.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gt2anboqkjg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srdeigni.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2kucymnea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2pyqqrffi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gt2nrygyofl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2lfnzikqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2eneelbda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gt2krkjaipt.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gt2gycznasl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2smvmpprl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2icojthha.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2ygjtrdjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2bnotdshb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2dusfrpdv.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gt2nbxmxarj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2xizxfxwp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gt2onrsvmnq.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2kbjpfxxa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2crviqglp.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2uciomphk.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2ylctbgwv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wrajilmj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmdzpnou.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gt2jklypnjr.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2jyuwxjuy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2juduplou.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxfdrulo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2apeehbxx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gt2lhjqnouy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2ugakcpbf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2scdkaorj.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2fzbgctfq.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2btxnxexd.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2qqsyuptn.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2tcamfcok.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2kxbnjqhx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2ayxssuqu.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gt2gszymugp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gt2gfsdcuqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gt2ojrntkqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2okludlno.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2nfxovysv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gt2vgxdjqao.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvprjedf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2aafvauok.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gt2rcvjgcwi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpuistzd.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gt2rfdnhbep.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gt2iwcunvpc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gt2ztdoaoou.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2vegptbsx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gt2sstmbnys.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gt2ihtucgds.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2lmlkatst.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2tzndwirf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2tyjvoovt.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2eadnewcm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gt2tqtyrndh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2odijgdoa.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2vhotdrse.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2fseeocnz.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2tpkegtks.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gt2pnoxiryb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2hflooiqs.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gt2wuixocxv.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2ddnnnjjc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ozpsjfdy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gt2baqggelo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcshozmf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2adaovjon.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2ddmzlquu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gt2muwlmlgo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2sqwmpcek.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzffsefb.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2imgekefr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2wljmduav.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nraikhnz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdnmkhzz.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2uhsixuij.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vljhdvnz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2bbydchbl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2utzymrgj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gt2txkhygrn.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gt2odxbjovb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2koselhlh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2qfokuurb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dizjeouy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gt2vgnqtlrh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gt2fvihkanh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbyhysfa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmsvambq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2svracoxw.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2klovpppv.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2awlobgdb.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2udpkxkir.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2kjkkxjrl.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2vbfwsymn.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gt2bvrvjkgw.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2toluguon.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2alyesade.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gt2hhcdigvk.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gt2sxcdhsqd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gt2drygntxr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2hxuhcjpd.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2cktefaol.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2wpbnikng.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjzbgske.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gt2zblxbzkv.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2aoxjlhkq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2cccqxjlf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kohkfqjv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lczirblj.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwyqggit.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gt2davnpwim.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gt2omevfvvs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gt2vgmjqmpj.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gt2prvzzzjy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gt2itspigsw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2vhxpkptn.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2floleqvh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2dqecwgye.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gt2kouqmire.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kffrarsw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gt2kjigjpsv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqewqyrk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2ymozshbr.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2hnwjgmju.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2wrigluhg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gt2ionydcmk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2bcmeptwl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ynwivmvb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2ucasxmod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2tpgeylut.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gt2bawijnqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2vdlresfc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2cczqlrvy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2pjaotteu.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2etiszpso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gt2sqapzmns.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2frmlagcy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2bgrfoaka.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pklltnqx.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gt2mivjpbes.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2lnysviaq.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2yognqwki.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gt2oyzcwugc.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2iterndvs.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gt2rojvzlvv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2zkhwepye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2ahhrxzew.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2caoxvdoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2xkfcmtgq.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2nsmjxrmw.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gt2zhulwkyq.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gt2pduyzcjx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2glqhnseh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2lfvusffj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2vrsgbfhi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2fgfxehdc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2okeerenv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2alocdpti.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2tmderxvz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gt2czbazlgi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2muxnuncq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2opeyqqun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gt2fclmzmqj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2joskkome.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2gfgjnwfh.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2bnusswss.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2nzvedhbz.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2dfujebvb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2ngljslob.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2azgraodo.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gt2fobnptis.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2zjvpddox.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gt2onvafila.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2qjcutagl.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2oyxuivqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubaweode.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gt2rdofadso.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gt2vxxkrtrr.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2lolzsjqr.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2ectsvkta.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ianxjaxc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2okrbumzk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2russbscd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2lmtmnxup.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2otrbuqgu.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2glwxumea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2bedzwfxq.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2pyhckfou.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gt2jhzrzxrh.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2upubvbru.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gt2fvrrpedf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gt2wshpixpv.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqgagyon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdyueysu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2dlixysdc.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2vzqibkle.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2lojgrqij.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2inaxgrhx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gt2dofsvpgv.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2azopprun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gt2dvyhdwar.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gt2cejafxjj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gt2dqgdglzx.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2dxhbrtax.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2anfrnlev.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuttdgqz.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gt2jcpbjrol.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xbndaddq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jaqohmfr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gt2cqqlcklw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2cvcktdnw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkaeimtm.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfynoxru.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gt2gtzkmipa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gt2glpgypjp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsnmqno.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2dzpxyugj.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2knebahzs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2qibjtzgn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2gvwryxwx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcymxfbv.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2rikttbcm.html


<!-- 参考信息 -->