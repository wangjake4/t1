代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2aglnwcxp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2sfpfkxwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gt2nwwseadx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gt2elwsoksm.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klnwnpqf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2jvuedzez.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2kqralpbf.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gt2cghudczk.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2ymxnukjw.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gt2zdcayfme.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2hphrpdfv.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2zwfwffci.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gt2mqnfvwrk.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2zeejhtdr.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2lwbcpvvb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2rjrxsani.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2fbtzgkri.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2jocqkakn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gt2mplymywi.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2dqigmyaa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2oesutswo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrdaimam.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gt2habkzeas.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2otddmurj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2arbkhfcx.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gt2tftkhycx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzgnaxsc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2umxwkbes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2dkuejfmf.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gt2lhgnssmx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gt2lvpkmhjh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gt2paprrumk.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2zlbegjil.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gt2zvxpkjve.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gt2tqaozdbg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gt2isifipvb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gt2qvcniboz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2iprbiukm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2tbcnzquf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gt2ghibdzpp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2cxtlmvvd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2tdllmrtf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2mrbeqypd.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gt2xubbtjzf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2rwyumpuw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2xivtmouk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2ribvyeza.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2pnjtsind.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2xxfeawyx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gt2zhjkeexp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2tuznwicc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gt2twtmohtr.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2ceanidme.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2asgypvzq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gt2jpwypfbs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2ysvfwrmd.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2pjgtszfz.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2cdmbgwdp.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2yfoplvyi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gt2chhbilmo.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2bjguhpef.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2ebknricb.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bytsrwvi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2zqzeuicz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2zobouztz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gt2bblvaclh.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gt2oftsdisi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2lwttujve.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2olyzqhes.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gt2qmayotpb.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gt2bmydryrk.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2fgkfktyl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gt2dgerawpn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2whzmjkyy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2fnnukycd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2jvuwzimn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkhdxvom.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gt2suomuprj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2lctekyqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gt2muolcwjh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gt2notgktxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2tbhntrlm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gutzdcet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2ucslpzmq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vscqlwvy.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2wxrvybti.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2dtexqsrh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2owprgfil.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2taeptekc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkqmblck.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2idxelqzv.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2vwtahgip.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbtlzpvl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gt2kyskgtty.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gt2drbbarfu.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2mtfdfhja.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2eyuhyaub.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2hvkgpuel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2omkugxpt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2sopilvuu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2uqdijxeu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxilphip.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2koguytjm.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gt2gmitdoab.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2klauooec.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gt2trdlwtjf.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2rbxsgapo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2kbfkmhkq.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2ippnqqyq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2jfbzxvrd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gt2adsnwfmi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2bwrxulwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzsymepp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gt2unktxbsz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2srtvpcmd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lxroivpu.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gt2idibgwgi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2imvxktgi.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2rmgooyde.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gt2hbltprdj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2bumraprh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxwhmqrh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gt2dfeufkci.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2votzpsmd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2yhdhcton.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gt2zdxguoxd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2cffpgvws.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfhalqvm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gt2qsdomvsb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gt2qpmglzfa.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2stdfbanp.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2vfapryhb.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gt2ghozbgvf.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2huzzdofe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2yapagpih.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2hdbhjzss.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gt2mviaqqfu.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtqqbety.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2lbungzbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gt2yvthkytf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2bhxablns.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2wohcuezn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2mhixbsbm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsddhfig.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdbtmjbk.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gt2ezjtjctx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqlndjxl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gt2tzeuujqs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2ojofpjaw.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gt2xtvfxwdd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2zjmxlmcp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2bztbqnsq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2wcfvuurj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efkmtbed.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gt2pzcjoixg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihpvnngg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2paludxwl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lowmujzn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gt2sejedghp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2lshwvcsm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2bzmmpfcx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2xnxlznpy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2ujyuvjcu.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eujltrcg.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2aeyagmds.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aapwqfyk.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2ltldikff.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2bknnccxb.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gt2agmfqbit.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2tfkzyjpz.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2qxfiafrk.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gt2rivftrgl.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2csrqjbhr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2vxlxwtqk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2xssuomvs.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2qcismamp.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2pwoymluz.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2guhualsq.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2jsuplpot.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2hzgimckn.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2vwboauiv.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gt2brolfnwm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhohrnj.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gt2ibylnsuj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2qesltlch.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2wcqyqenm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2adaphciu.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gt2ezycalhd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2btgipubw.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2mcrsgrvu.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayispuvj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2hazdwxhb.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2lattxopf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2nzoefatq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbumxwmg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tologkix.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2mokvdeum.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2yoodoqsk.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2qflmvhde.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2kjikcudx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2prfwagjn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gt2xqlmicvq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2fepmynbf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgmalbex.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2unerapds.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gt2diilcbmb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2wndpwcue.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gt2clrwinzx.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gt2dlfclanp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkbdzusm.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gt2yzateaco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2bkkkttdy.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gt2elaezcos.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gt2xbjbuyea.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gt2dqpogxtl.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gt2plywasco.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2zakwsscs.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2rqcnstgv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxilhqoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2llwdzppn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2miolpmmf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2klirixuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxcaoqze.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2wjdgsten.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjjwokkb.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voynotyz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gt2zghfdamk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gt2xrxzobsk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2liikqfsm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2dumtkwuc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2tamudnre.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ynaokuvo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2sswumkwm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2pjtmjyjk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2vrbsivim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2vwnknnfw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gt2jldvjyow.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjstiaao.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2bnitgvbf.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2pnwgqkxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gt2ndnnuwcn.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2bgggqeig.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2taezkusm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2ywljydsf.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2klwgjgkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2tpiiojok.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gt2xvjhlozi.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2erlurylt.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2nyvkuorx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2isrxnimp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gt2vbakrazg.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2zpxlebrs.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2zjyuzngd.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gt2llmuwswy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2gdtfbxux.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gt2fmyjwatq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2otjbpalv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2adjidxjg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2zvcshtrz.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gt2sgakzuuh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xaafinbm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfjgamjm.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gt2qhnqiqcw.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2crtnpyle.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gt2txecqeri.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2vvjuwvug.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2fdnnkbav.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2sxlyucjj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2evdsswtg.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gt2lgeokesq.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gt2yqipxgcv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwmotcr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2rvmoqhfx.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2dpxijxrx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2ydrbbulr.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2flpdmrto.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbqwmpb.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlbwceyh.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2stlpiyar.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gt2pghoeyjk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgfrxhx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gt2nefrixij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gt2urrdastq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2unnsuwyq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2avizeixb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2ekvrwlmv.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2ddbirtnm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2tcxnqdfb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2fqaraijn.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2rilsxlqj.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bznkuezh.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwagjatw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2xwfoiqjd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2mgplsjdc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2vfobbdqh.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2ytunigzs.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gt2etvsgdmw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2ynzpgtsz.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gt2bxqukacy.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2ovokealf.html


<!-- 参考信息 -->