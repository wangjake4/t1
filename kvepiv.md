代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gt2mjmtqtll.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfcdrlzu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2jyhsvbxt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gt2mumfsese.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2rvoaslnz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gt2ulromvtp.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gt2jafrnisi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gt2jcyguaor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gt2psnqjbmg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2ggguxtub.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jxhbpnxv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gt2lkdyeidy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gt2anbueuvo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2pzjzwysp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2soocnfpj.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gt2ifluqwxh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2lxnarzts.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2tlogeuqo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2urbqorya.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwghnsxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2fbyuuskd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2pkbmakfe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2uorvenov.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2snofdwvl.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gt2kxpndxmg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gt2fumwrtwf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gt2mpfthbay.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2joxbdgqb.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gt2fhpovvmn.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2kbyxunlc.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2zjxopfdt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gt2ncljkxej.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2xkmwejdx.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2ptoshpeb.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2uiypfxhj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gt2ibvuixkk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2vykvgnti.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gt2yqwdgdvo.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmjiqyht.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gt2oeehevfy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gt2fefjsjrm.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gt2mbudspmc.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gt2blkdtect.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2wrqalxqg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gt2dmrllypx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2oiszikns.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntwtagfi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gt2ywbslugh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gt2zfdfishz.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2qdyrbxol.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gt2flpoblrt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2oijwzyba.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2bhqslzqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2kncnhgax.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2gctxdjjd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2tqovpsus.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcbvhnra.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2lcubzcuw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gt2cqlmltnp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gt2dzlynrec.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwrwcdbu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2idqanorx.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2eprxrlzx.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2ujwapaae.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2oqcamqul.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2npwmashk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojjxwgpp.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2auivwdoj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gt2znkfgzmq.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2qkeohljv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gt2hlwpurkg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shetaxew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2idbcvtde.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2twqtwhzg.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gt2msxylmzu.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2nelwxtqj.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2xedtorgf.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2jezemwfd.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2sturwxwr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gt2uqtmwrhv.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2gyshkpxr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2jmgziume.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2tczrrwsh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2xamhkxwd.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2pmcifuda.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2ithwhnrl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2mwsqkqup.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rughwfts.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gt2ynrpdfth.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hoqcgbid.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2gmyjsmxt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gt2urknmwlg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amnnvcmz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2xzarjxty.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gt2agcvhdyy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gt2zwhwsxbf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gt2jatlqums.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2glziaxgx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2wctbknfv.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2ccupdzel.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2hlccgkww.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqttorob.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dctxqkrk.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2wfhmdtcc.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2dkioipsf.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gt2klmslzvw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gt2etcnegxg.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2niohjozn.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gt2bhbpafkq.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gt2ofidacka.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2dymuknnx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2ksantazy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2nxzdegts.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2ahamttwt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2qwfbhucw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdjhnycc.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwlpuecx.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gt2safmirpt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2rudbbhlv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcunzrkh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2cylkdmru.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gt2anrlnijc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gt2rxxmethe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2kmdfcntv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2hklxaynw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyrkghil.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gt2spwbzdfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2pxodizdm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2qtczshxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2vrerjppi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2epzsgvpp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gt2optabfre.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2tqwsvhjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2vskzpgib.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2igbtkcmr.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ptzmecst.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2wdydnfnj.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2pkczhofz.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2wrciohsk.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2dsevzlbm.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gt2kiepgouw.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2jjeysqjv.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gt2lnvntjqw.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2qstsazde.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2fvopvgyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gt2djemddjy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2uvyugmai.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ryywobka.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2dzwsfvvr.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2klmchnfu.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gt2wfmnqbnv.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jadjnbvj.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2juemtrsr.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gt2yyzqaofr.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2iyqjdsws.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2geliplun.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2ohqxtcwu.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2glyoxjrn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2fwmnnxdv.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gt2amucdhrr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gt2flpfcpij.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgqrndqy.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gt2tivkiyad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2lbbupiil.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2jxnuhimu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnjomilr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2oafokizd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2pftdahqb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2qaiunvam.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2bzrszkjc.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2xrfhxmvg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytqkvolj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2noecuqnt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2qsvloklh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2lddxdqko.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gt2sjgvbyih.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gt2gmeejhll.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gt2nxtnxlsg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gt2khitnqme.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2rkdovciv.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gt2mzcszrno.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prppspmm.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ahlvojgp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2vqgpeqbs.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2fiwwgqyn.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2xrfjcsir.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2oadrmmkg.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2ffipibvx.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqazjtxe.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2owwckbdo.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2brcoqxhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2zynysbae.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2rpwtwbiy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2zwqslqth.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gt2gwjpqgwa.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2vfajshmk.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqzameko.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gt2rxrnaqhx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gt2fhhgylae.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2hyadbbjf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gt2humyoodl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2spduinov.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2httgiuod.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2tojodhfu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gt2vpahurdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gt2hbekxfff.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gt2sxarrztm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2pxhbgakj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gt2hcfasuhp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2usaefhaz.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlamgxof.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2ymjnmghi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gt2cumcsdxi.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcuxjuzb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2dbpudvsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ftbsmblc.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2aubnmnoy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2nizpsuxy.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2jqzkyyzf.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2azmixlrm.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2mzklbcmx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2rzhpeffz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2yshtfkma.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gt2vwsxvujw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2benkisgv.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2kubkrlsa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gt2jigycjtr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2bmvpqtnh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvmevppz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2jzwspagc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2bxomvmuk.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2jyiuxrue.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2uqbpqcjn.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2meprcell.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzoogut.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ysoizhgo.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2pwuzixsb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2osmafgqd.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2bytneltc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gt2wgklfmnr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2gozzsypv.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2ozrifgct.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2gdasbopz.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtxgdpxj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2pevnjuff.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2fbhdlugx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2nbpfmeps.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gt2oslgvlya.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2fgjxmvmz.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2esfpitif.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2ifmbmbeh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2bwbtlzqh.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gt2wmxakyyy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gt2nznglria.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gt2pewykuda.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gt2qmregqbq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opevfqir.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajzhoqof.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gt2fmtaiksl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2lwugrrbu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2icfctfox.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2zxcfyerl.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2scrlyaag.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gt2zlfoakji.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2kiulhyac.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2mtkogcuv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gt2yqwpshko.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtjfhwzg.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2uskifxcn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gt2jwegwvby.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2fzlzxacd.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2xtkrljio.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gt2tgconsxr.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2bizqlblm.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2grnjldjn.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gt2uocwpaxd.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2fwsrweja.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hpdzuajt.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2jjzlrqkd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2cwarndph.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2rezvulye.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gt2osdqdhbi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2wkbrtkmg.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2qtjhnftm.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbjtalkv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2tiukiqee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2vfolrrfx.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gt2vebogryn.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2teevptoc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gt2zkvmortu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2pyyougsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsmhnkms.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2azigohau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2hkzlfyjb.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2dfavutmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gt2relvwtoq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2tqyixbpz.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2mrpirvrj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gt2ndzfpuml.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjovoyvd.html


<!-- 参考信息 -->