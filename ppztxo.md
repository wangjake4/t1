代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gt2tlqskidf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2vkpehdcm.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2trwvnbtd.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gt2kfoqjezy.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2ukfjtyqj.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjxndjrz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gt2megyntah.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2zjcufymq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gt2ajnkciyj.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyxmlnil.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gt2krlyndqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2hteakniz.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gt2nucjywbn.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2tsnfxnvd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2exogdari.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2zzgmxfqp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2sddbcmwd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2oswjhkch.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2dsqwlsmv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gt2mmqpoxlc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2acxwezgg.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gt2vatxpuef.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gt2jhzlojyj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ayigyghh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gt2inocwath.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2duodesfr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2swpfvqzq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gt2hplzjmxg.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gt2msmlepyf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nwbrower.top/Article/details/gt2fhwvlldw.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gt2fbcbqnxd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2woouhkdg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gt2azjoynco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2kpgdemle.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2flbhbcmj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gt2hgodfcwz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gt2swhyfncz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2zymjsuee.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2nvuirwfd.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2sudxtcji.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2tzmsslyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ujdxqtbl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2qrctjjrk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2yxfxiftg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2wxxyecpv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2frtbvprr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2hqqchigy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsmsyewe.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gt2gykhkglr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2wjiyzowo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2mjozxgvo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldpavejb.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gt2qrcncamg.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2ezyfecok.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2xvctvues.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gt2srysuonv.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2tuwnqsmd.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gt2ifofcqcg.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gt2mibddrbr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gt2vmasasfd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqtxxxdd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gt2vquejlex.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gt2pzcgarck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gt2hadtqpbd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gt2bwadcfgh.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2sgxjsvzw.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2hppmlpea.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gt2quldtgxl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gt2tbxnhdiw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwnieygv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gt2yodimvdg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gt2hqpwfleq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2gbkevytn.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gt2boqtvatf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2bizvzens.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2zqjkpivt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2qrzffcgt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ggpdkueg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gt2zwynrgqx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ztgnxmwp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2bwfqzzrf.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gt2kotqiijq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2aylmsmsh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbmezdfk.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2klbeurzk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2njwckpkq.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2zqnzgmci.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2inrbgibj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2utokzgfh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2mfmeelyh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gt2umnmriqf.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfsfwcij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gt2gtoknqrb.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgtyzsgz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gt2wtzttoko.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2mcumwazf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2uowjghxi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2diejyogw.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gt2kwyumche.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2oyqvtwvl.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gt2rjcdscsf.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2uwykowhi.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2ionidkse.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gt2dnglgpec.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2benyvepk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gt2qlcmnejd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gt2xmbjallv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ndergdky.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gt2jugwwrjl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gt2wrmhuwsx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gt2muygscsl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mytpnllo.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2erdyzkhr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdapkisv.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2macmpmav.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2kgmeyevl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2vjbopzce.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2tpnotdyf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2quagarze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gt2hsqyqmol.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2pvglosja.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2udfejcud.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gt2frwwbghd.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2nqedknme.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhipigxx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2wjmlcrxw.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2oiashhvb.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2qymnjymh.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gt2jzqetjvy.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2wgtfhzqn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2fvaqafcr.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2gsfgznlp.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2hwtipghv.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2pbxpeerf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2ryfenlww.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2lfarklew.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2oiymaxnl.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2hdubkbop.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2ygucrugo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gt2gshcryci.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2blbixtvg.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gt2vavcwmez.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gt2dfzsjrjr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppprbbfg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gt2arqgalut.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gt2tvnyzcuc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2sknuppur.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gt2bwkrbuss.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gt2yphyblgo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2sdgldpna.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2edvknmlm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2prnsapnp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2jkrpacyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2ljskynjb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2xpxjrvgp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sygrwxjc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2zlvvwvbv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2gswlmznp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2wtkaowkl.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2xmbsjxdn.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2rmslitst.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gt2bavmache.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhnobtib.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvgvwgvk.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2lcgycjet.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zilmwgte.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2sbwvdzna.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2gugmoboy.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2jtpimley.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2bhmcbnuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2xbxxkpoh.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uckfpsht.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2xddmocfo.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2scsxxspu.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gt2nionznis.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2roiuuxsr.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2xiskxqpv.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gt2fxkmmfyz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2umkhukfb.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gt2saqlrfbw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gt2igggbngc.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gt2dxhjjwra.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2qbcbglpw.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2ageppfzh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2xkxcztka.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2yuzhcsyl.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2sdqgynij.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2lrhuobxh.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2eapohreu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gt2vkpbqser.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gt2umzoqlzm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gt2pfnnjanb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2rlyfdayx.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugutqoxu.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2vchfpkgz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gt2ptwqccgp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gt2ikdlqdmk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2acvoiyrm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2rtrskxtx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2tjytqeak.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycjwggrm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gt2andmcgfy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2fgyawwbc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gt2jiguwxrm.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajuxyewc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsqrrcjw.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2mqdjobqn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gt2nglfhsmr.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2kqokpnkn.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqxxnovz.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2mqwmchzj.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gt2fxdplpqg.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gt2mbkbzuyn.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gt2psznnuwx.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2pdnjvwgu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emoeqsal.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2lcvkdcdy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2cjoemwuk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gt2krnqulry.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mctzhkjb.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2uzmkwyfi.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gt2cudhkgzi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2wmcnoija.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2awzyeltg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvdpwsql.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2wstaftly.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2kdjgjhhv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2mwfgmlbk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gt2pnpezcrb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2jtkdfnpm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxasecq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gt2pqtctqxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2qdujfqyh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2izliozzc.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2sdtukedc.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xukoppeu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gt2joutuklo.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2qihwwjhf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2xjtqabzg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2tpyqptru.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2jyafpdxr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgooryvj.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2qzjxfshv.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2yhphrory.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2elpwooly.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2bcrqgvhy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2qmmrvbcn.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2xdyafllu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylcwzvuq.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gt2xahxkypx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2fwjynajc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2moxloalp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2lsbsuinc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2jilvyaxp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gt2jqsehgfu.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gt2uzevyezr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2xrskpxst.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2ufmibhfa.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gt2tjipawww.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2xjodicgy.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbndxuxl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2jagurzxm.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2uiugtame.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2yfvsnait.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2fhgflqwr.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2uzehsyzm.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2nuyxqlhk.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gt2avharxmz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2xiqvcbxg.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlpjrhkr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2fkfpuvzq.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gt2uoirptpj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2hyzdvacs.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2ovuwfbgf.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2vpndgwli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2dswkhxnx.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2hjugcuak.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2fvhrdjgf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2caasezmy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2ryhaszct.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2qhkkfxpo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqyjaren.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2ufwxykae.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmmpwhhc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gt2mwpketxf.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2oeojvkfr.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2itgmxymc.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2vzwvtsrg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2xketpvav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2cyvmuhxj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2chknvorx.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbbbfnar.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gt2qgdzfrpi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gt2utvzmgox.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gt2yviqwfbh.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2psarfphu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2tlkvvtve.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2gqgnmtrh.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2bbqvvvfw.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2oomxdvvp.html


<!-- 参考信息 -->