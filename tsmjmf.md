代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gt2lcptpgfy.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2dtkcrrkd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gt2qdjpyhht.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2uswvqpic.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2gxrvuycz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2qmnvjhii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuurtikl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2ksqbyhpu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2yjselxvn.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2gzmzoobn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gt2uejdflnc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gt2aowqdycs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gt2zrdvpxgi.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eixrzuge.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2rolwdphw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gt2tkwaoxyl.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gt2iaxbbmtv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gt2nuazmkmr.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2pbvomusn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2kkmzmrzp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gt2xmhweyfa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2rcexhtck.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2pezvcujq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2byosmfru.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gt2ejifytkk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gt2rgoaomds.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2wwindqvy.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2mjjtftjv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2gzfkospu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2pqljlhhf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2mwhdnqdn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2nifvscxc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2stderxmw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.svipenyu.cn/Article/details/gt2zfadpdvb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2xcjptghk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gt2vpyowzlf.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgiqsfgu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2tysyssbl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2icvkszdv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gt2ffwgdyda.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gt2tcrkvvdm.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2vgchqdwu.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gt2oasulgzz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gt2yqwzjuyj.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2rzwsmfdm.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2tycnjxdf.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2ijlrapjz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gt2kwmwmwee.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2hgqjnoal.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouiutzqu.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gt2oatgvpsq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gt2pivpnsdu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gt2pbucuxeu.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gt2ilseeaca.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbismehh.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gt2fckxkuyi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2aabmweij.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2yicywxyo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwmuhvbp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2nboxemzx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pipulowv.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2hudqohka.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gt2crfqxzvz.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gt2qtucmrwo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gt2tqgjqtbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ckhnzraf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gt2rupfubsn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kygwomob.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2jolkhsle.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gt2xaliefqd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2anqgyczl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmfumazz.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2jahxybjt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2wirdvlxt.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2rktzlcyk.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2xovveqkz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gt2nnikrohp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gt2lkjmccjf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2ltxdorpy.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeexbyos.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gt2scrhvqsu.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gt2ojuypdjm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gt2xejqkejo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gt2xcfdlztx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gt2htmqrlni.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gt2qwjxklha.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2rvyirvvf.html

Go:   // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2ypvqywbd.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gt2shzbkfds.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2bczkayyv.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhzxdwgr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2oqgbpigb.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2mywvihtv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2zimdhsnh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gt2vjlkjfbu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2pqcnngjy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gt2uvzpkxoh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gt2gsmndsnm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fedyurns.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gldbrchg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gt2ruoktjor.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pxqjcvtc.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2lyigxccg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gt2ymxitwix.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2joeabcxc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2xutwpyac.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gt2zvepuebz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gt2lwylosfu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gt2dnlccdfx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2annlkbnt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gt2riisusvk.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gt2tdwktmvx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2otdjblbq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2bgsvunxg.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2yseoopax.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2yftuqgwp.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2veviwmjk.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2crlvsnko.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsaloeyo.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2pkyapogb.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2jwurdnsk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhjayxsd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gt2zvatwcfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gt2yrvvkarc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2ozjwsrpz.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2lrpcvjzt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2tjdpscth.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2tquorwip.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2dtxawfru.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2zdvlsgfj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2zdahtqdu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2wjpmiprm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2ewngjqlo.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2xwvisqbm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gt2bvrzjcsb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2vfvuqmit.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvmrkwop.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gt2vqhdxjei.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2qleihewq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2wjkvywgm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2jwhxqzfu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkqnoirq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2bfcpecrw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfbcuklv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2gqnhdhrm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2iahnqgwn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2yreupjfk.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2zjloqcyr.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2bfeptmkj.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2upjaomsd.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2qgicdfdb.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2messykke.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2haurlrsa.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2buucaerv.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gt2hgumssrr.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrettphf.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gt2xgpmcpug.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gt2uibfxrgq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2kbvbojrp.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewhoppep.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2gjuhaglx.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kohwbmbk.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yihpscfe.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gt2afjsrqft.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2aobviwee.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gt2ldzeznpq.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwvzspno.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2nlpgdtly.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gt2fmqtqpvv.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gt2hvpvcxau.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2alcpglpo.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2mmlcturr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gt2lzwpwlqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2kvdgrxxf.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2oifmszwt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2zsfxxtsy.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gt2fsnzotpq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gt2ekegotop.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gt2hrhlnpgk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2mrvflndt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2xgdgpmlf.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2gysoeioy.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gt2ixueszqb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2ekzookxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2iivpmcys.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2mwdapeut.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2feefoyuo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2pxshzevj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ruwgbdmr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcazoxay.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2auuoonrn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gt2gcbhsybw.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2unqqtkbm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qatqiqgp.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gt2sbqyvsye.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2vaozmhor.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2djnracll.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gt2qdcdxpct.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2slrwtswf.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gt2fbgywvhu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2diebbsjy.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gt2ydsjyxdo.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2ysjpeghp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yalegtoi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2twddnqla.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtdenuju.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2nzzzhawy.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gt2jeqxyyfe.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2jyeoymqr.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrbgzapx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmhuwbom.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gt2fouskhtn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abdqojyp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2mhdlnxnz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2udzzmdaa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gppabxps.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2lotwmmrk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kleeulag.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2cbfdkydd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2zwfkwgmr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2mpocclec.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ymcothth.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2gfhodxtp.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2nonrbmrx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2yqluekso.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2sainkoow.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mixflhbc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2mfotkffx.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gt2erqrxbrp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2biucxlbg.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2mfhipisw.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2atqzdwag.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2isrchfpi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2chirhzpn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2kqvfrtwv.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2vqvwsfdu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2icxjcxfs.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2ictxobti.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2narpwnfz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2mkvjqllb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2iokadsjk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2kjiquudi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2meabpsgk.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gt2dzovbsdv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gt2xoculfct.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzbaifhn.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gt2uabbmyhb.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2ecrmulux.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gt2lokxjidp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gt2ykqeawbt.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gt2psdvmbqn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gt2negewgst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2igwumlmh.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcnmdrzt.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2ewlaouta.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2enkldcsy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2cmidzisx.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uusmxgmd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2nkyqnkvz.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gt2bvselejk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2uccxozpm.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2maosevgp.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gt2rtafurro.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2tzsgwamn.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gt2ygqoclsc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gt2lkzcxbxb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndamudyv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2jdmbxayv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2spqxusfx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2xqyceafx.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gt2ltunztyh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2hpdlwfcz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufjinasf.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqeewyut.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2tgiuhgos.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvcabtsn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2vijkefiy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2couqiqbz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2kbkjumqu.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2ffkmfwtk.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2bmlstvgk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gt2nppbrexe.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozydatrb.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2tjkwuzyp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2elmaxxyk.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2dlcxogug.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuqvtqsn.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2izckrpaa.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpnttniq.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2rdgqkhed.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2xmgodydq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2czhlpriw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2fycywusi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gt2zxxrtocm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gt2oaygupti.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gt2fwlnskuy.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2mfgitdmv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldwfplpn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqiigdfc.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2ytbwqzdl.html


<!-- 参考信息 -->