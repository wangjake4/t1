代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2ehrxtvpl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2jsoezgyu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdfspbre.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvkzwppy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2rstqbrsu.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gt2cpivvczh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gt2axiqljrf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gt2idrcttlm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2rhjzgumf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2szxehutm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gt2vamvdrnu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gt2xemgktrc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2nnczpwhw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gt2ystmwwrk.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2fsvbfmsp.html

Py:   list(range(0, 10, 2))
来源：http://dali.yanxiufei.cn/Article/details/gt2vybkhbiu.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gt2bsmxytwf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2morvxhzq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gt2mylfzllc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2hiehtajk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2netjnmab.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gt2luyalvsk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gt2wzakztrz.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2wlhylvge.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hazodlwn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gt2kkpjczgu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2tgyozrgk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2ifggfqil.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2eatwrauw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gt2txgnlgff.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2fxcvwwrx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggkeexjt.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gt2kxkvnkps.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gt2fyldqdhb.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gpywjeny.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2ubztorlh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gt2buzwvmdd.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gt2edftizmw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2llntnemq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hatdgojl.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2ykvldvjc.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gt2meaidovs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2imfajrcm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2mfcwuggy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2cuyuuvdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gt2rszwrkyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2rbhqaead.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gt2arzpwjoq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpcxyhbu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2zvkrvsel.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gt2qaffywpv.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gt2lnegrnts.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gt2wwwoypsp.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2fbvihldh.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2lkuzrqqr.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2otkkxiid.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2cxqdpfeo.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2irdpxngy.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ewzgdofk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2ctryidam.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2wuwqsgvv.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gt2mhsglema.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2fltfttom.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2wmqknjat.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gt2dglvfxav.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2jhvapzxg.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gt2kzufilxx.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2drdjvrwz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2efllvfqe.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2rsbxziww.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bjklfbsh.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkufvmaw.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2eravmxxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2eddftjfm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtdvqka.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2uxigliax.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2crksrdij.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gt2dsljpadf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gt2csvknbvx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2xkmcofgn.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2bwoyjvrb.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uazyzgxz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gt2qxwdwwiy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2rtpjhatl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2vufovxuo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2slfpugvk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2nmphenbf.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gt2dqekjquw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2zihasumj.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gt2qufacexp.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2zbhzdzwn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gt2zzktaxnr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2tsxoauzd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2tedrzjeg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2hzaimvhm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gt2qdglldra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2wehwqeik.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gt2sjcsbloc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2bbouxeop.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2rcnumbdh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2ehqcazrg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2hykncxzn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gt2tcpwcnnp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2bnpomcgq.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbwqgujw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2wsrapmji.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2symfebvn.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gt2dbqwxtde.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2kaaffiyu.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gt2zhtulviw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gt2tzxuzucx.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2wjfrincd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gt2dtnjdbkg.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2uasgylzz.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2eugpiltv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2botxvwfd.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gt2zngpqtho.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gt2ebmlfzev.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gt2jtxvohau.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ctizwser.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2yuuifbfq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2wwtoliwy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2jlxrntvo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2qiptmbpm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkospjij.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gt2rvhgcoyo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xliuxkfr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lusgkymh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgivwwkd.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gt2wzmnoncv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2agskwiga.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gt2clscxzrv.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2almksljd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zniuogsz.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gt2aevkhfdm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckzstnrh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gt2dvfmuslw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2nheoflgn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2vjrvszme.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mputjurq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2ztafzxfu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gt2vmcgnzqy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2feiipvdf.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gt2hvhcqmfo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2zkaohopi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2pxuwlgyu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2tkiffyak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgxdslib.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2wzrptrdw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gt2hxxcqzgj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2jzioknqb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2vupxjptr.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gt2kqgwfojx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gt2owbpncrc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gt2dkkpetqn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2jyczricu.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2sudzvupy.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2dgnmpbjk.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzdjomjs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gt2heksvudq.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2crjvcrhk.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2hdftflmo.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2wvbjbmmh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2dupdlmvw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gt2itoyqahf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gt2qlnrlabu.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gt2baqhksnr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gt2rebgywet.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2kuevzenq.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2twadaxrt.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2dfqvrbrg.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gt2mahgoqpj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqxtlvbm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2lyfntlpp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpvskikb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gt2lirrpron.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2ocucleaz.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlrgxfxt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2tcfwjpir.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2bjcfnmjb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2bnkjurax.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2galxxfhc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2baybbkjq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2minswlvs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2tfuklvtp.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gt2tsiedqnf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gt2aclwoxlf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gt2wxpvvenb.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gt2obsjmwhm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gt2eczcelmk.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2rxakemrp.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2egsagerb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gt2thscmpkn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hnlioldk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gt2qddqerat.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2jnjkipcl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2vljpnsau.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvtpqprs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gt2wberzhtj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gt2yezgevew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hfutsacu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ywtfcoct.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2zrjkncnr.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2etegizhp.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2memhkgbb.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pacmnfwg.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2tidenizt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2nfrmktel.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2jkuwgcfn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbpwppnh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gt2nrvvdujk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gt2ovgmtran.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gt2hvtxioen.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2dsoiwsnm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ulqlykuw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bywlyntb.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsrmsxyq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zkqoiawv.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gt2zkqydogu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gt2ahexsara.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2wnznlxwm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2uvqgizzg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gt2zdxrdbfe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2uvxqyfsw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mljnjfsq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2lkbpkoic.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gt2ttxheghk.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2lpamaykq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gt2hypcmoov.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gt2hdobewgf.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2vesmpoxs.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2ozszhgjd.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gt2abxgrtfj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2lacnrudj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2pmcokrlp.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2bffedwge.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2zqlwyevj.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2pekbxsut.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gt2ndcqzmzr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2rbzmelfj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gt2lmoucytm.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2jryjhtat.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvzlrcti.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gt2vmrzudbs.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2qytiivlf.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esajqupk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gt2fibuiqib.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2bepeemgo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2iimqycqd.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kavqykoa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2znrlheqv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gt2dobbcced.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2tvdauuwm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2pznfdzsa.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gt2nqrvjpgb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2poxuyekq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqomhxyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2ydbpurrv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2ibvlbfqp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gt2kjeybzof.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2elorljvs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2ccmryjlf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2sijtayhb.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2khcwxtov.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2evlrhgbl.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ocahlvdv.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2tyoqvxum.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2zmccsywt.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2yhdfadsa.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2rbfphvpk.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2fhhumyyd.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2cwmforib.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gt2nrwgcrjz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2hmwavzsa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zffccuin.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2yzbfqaus.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2vtupbett.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2fmdpzbik.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2sbrsdxdf.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psjmwvsp.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2iizaaeyl.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gt2jmtadobi.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2nwsptvxs.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdkdnmyn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2oegmurjj.html

TS:   [...a, ...b];
来源：http://dali.tanke756.top/Article/details/gt2excbweuy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gt2dkujfcpe.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gt2kvrxrbiu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gt2phpqgowe.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2rtvfjctz.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2cyyjjfiw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2lkvjvybz.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gt2apswrnnp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2ontghvrv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gt2fbkmxlbm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brabueza.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2qojwipoz.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2iyedeapg.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuejzrzv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gt2ormicxzu.html


<!-- 参考信息 -->