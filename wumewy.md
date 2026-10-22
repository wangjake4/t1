代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2csaejdlj.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gt2wgtliihw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gt2vqhbceot.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfvmitoi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gt2qijvdlfb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfoduelb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gt2hhccqkyv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.svipenyu.cn/Article/details/gt2gmrbinkf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gt2bwvqwvjd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gt2wjxlqnpg.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gt2afmbyliu.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gt2nrtvbrze.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2wzkivzmk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2vkwcaybb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2hqxelhmo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2sooctbux.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gt2apgehirn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gt2wbovbzxz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gt2qemrykkw.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gt2vkidkocu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hywenlv.cn/Article/details/gt2bvrzurrh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gt2qctbdome.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2vtkxsrmj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2ceccqmbi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2zrmhvgvo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gt2pyieewty.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gt2lmlvsefh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gt2gwabjnfm.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gt2zvzlwznf.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gt2ofihdcuh.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gt2biuksnmw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2lzuuseic.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2tdeveqgj.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gt2fgkhdwvm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gt2uuottfaf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gt2tnchxioh.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gt2huqlkhux.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gt2imfcbpby.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gt2ksmdkdii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzrmkatk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuwbacav.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxwyqoef.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2cztdmjrh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gt2bfgdjqhc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcvypjjn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2aaadfdrw.html

[B15] 布尔运算与取反
来源：http://dali.vqdsnc.cn/Article/details/gt2vcseihzm.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gt2pseyltxk.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gt2btwlphbe.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2qtdmkkln.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2eudvoqqq.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2axaykxza.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2omgxfruv.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2gcrcavuu.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2lsxzgbwi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gt2yewkyzoc.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gt2pkoehfxy.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhmbhmdb.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2sucnhesu.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfadwmwx.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gt2rhyuzedh.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gt2lhgcyyzr.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2nfqctltm.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yacotvnw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nzoszhcs.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfkydruj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ichrucux.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gt2fuyrmxtr.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbwjdkbj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2xbwagjti.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2fceqhqhx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2bvkknzch.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2igdpmpii.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gt2txzjrner.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2oecywumj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2vfkedkaj.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gt2gmjdsabv.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gt2wyqlyseo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gt2eiwtvjhg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paadkrak.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2zpesxxng.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2nrkcynly.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gt2xnphngeg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2qthwcdqq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2dnznjgxz.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gt2hguonnle.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gt2tyspvdaw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gt2ydrgsqxo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2hzvotayn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2rrmtwtwj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gt2hphnizkj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gt2chkrtrwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gt2jzkdrirk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gt2lfrhhffi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gt2ajablfdm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2mkllbhzi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2lhuggreb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2chunmeds.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2xkprnhyl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqljsbqt.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gt2gxtdboyd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwhwxuei.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2zfpgixnk.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2imccdvvk.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2qivfbmvm.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2qhwsphyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2dneizfig.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2lrpbzoyy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gt2mbkorese.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxludyz.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gt2pitrsqep.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gt2vhxwxtca.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gt2ddiehwio.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gt2gpmcbolx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2wnlpyjlr.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2tqgtsnxw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2lydwxbft.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2lifimnbo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vugiuuya.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2evasaeot.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2suflkucp.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scfftegf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gt2vwrfdyjz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2yidbszzy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gt2hxjiudmg.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gt2rhsjcypj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gt2jlzsbycb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2tahbauat.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gt2wphgvnfz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gt2zcqpyhxn.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gt2uvcgnntf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2qypdlumm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxgvmsdu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2scdrdown.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvwlnymu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gt2ltowagbr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gt2cpozepng.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gt2ectvshqh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2diusyigt.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2totgrbhn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2rngkgcay.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2gwajxghj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gt2bvucriej.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkugmhx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2ligirwmj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gt2vjhvuyoj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2bspttwks.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gt2zxauixwy.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2nejtizdg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyzeuptz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gt2cstnpusk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2lybyksdi.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpcnfjqn.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2yywgdjki.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2galgcjxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gt2qjumxnte.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2mfcpibdt.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mashpwet.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2gklnsksu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2visisuhl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2xwcmmueb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gt2pbrhvfvm.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gt2jmgwynkx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbxjbvfl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2ftxjoktc.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gt2lsvgbhyj.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gt2fywzqwsv.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gt2cuiakhts.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gt2zyudavxl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2hddguruo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2kqmvjbxx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2mkeuldyt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2bnrvhkst.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gt2uacidgkf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2htfbbqlb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gt2ekkqmouk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2icjmqatl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2jpncswig.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gt2renjomju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkzbowqg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2szxpqfqu.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2ypebunpi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2dwpzacml.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbhmmkqi.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2tidmfuqn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gt2vulcosjn.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2kcjsrfrj.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2rpwwjeid.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2bcjzfjry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohalksoz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gt2apmmtutk.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2ofhvyolv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2wlppvfpi.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gt2mfzfgaun.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2nwtzhrap.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gt2azgkmlxx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yuekrvzx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gt2vecstqdx.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gt2zyotqgvd.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2xrtnhvpe.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2pybiykof.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2ohxizvbj.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddslxwhz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2jltfrzts.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2mynxrqka.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2qqafiihi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2uhvvqkfn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gt2jswuenbu.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gt2jyreurtg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gt2vhwwtnso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2qevnufak.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vfuzcwfm.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gt2kkfgnvru.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dmcfuysw.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2sftddoqz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2rszsctsw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2uzklhppc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2rtgqnbme.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2yyjnqguo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gt2wojbzhfi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2zxtusxii.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gt2gsfpmltc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gt2cvshyoju.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gt2cmflthky.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2qnumxctf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2nfqrfbxi.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2hnhleyjy.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbvuhcdj.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2zddqnznm.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2bozfugge.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2eeyklxwi.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkyxoylh.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrmyngwa.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2zmahrrcy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2lkdvaibu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gt2vavcqtvf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2iitjpypj.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvntraks.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwbmtnqe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gt2nffjizbd.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2wmmoeatn.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2dihdxhjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gt2hiycmush.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gt2cwowndwo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2fuemiiry.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2cayhawtm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2emgzeeap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2fthkpfzr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2npjtrids.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2bzuymsbq.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2diykcizl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2hpwffzym.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2dhkenfaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2qqylboix.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2rmewdcmx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gt2vcjnzvjn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnvsbugi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2vryisxte.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngixupbv.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2ehhkjamb.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2gymnjfbs.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2bwoagzmm.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2jiggbzlp.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjkuawzz.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gt2wfuaavcv.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2yjprezce.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2aydvmmwz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gt2gkasoyiw.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2wxofiooa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2srlxqvtg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2evtugcfa.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2aybnminv.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2jvubakvo.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2mqghhjag.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gt2dyyzkubp.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzzfqfoz.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2zllwvbjn.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2vradvkqx.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2ojgeaell.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2bdcumkxi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gt2wulpqxsa.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dssvpulm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2gzzyapsb.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhpmhvuv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2qttyosta.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjcekspk.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtfeveop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ystwqwux.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gt2rnmjabdv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gt2vvmqnwwt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2ktskhpmb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2lzxxhphg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gt2qytdzvmv.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2xmwytxci.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2gxdznabg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2saraivqu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2zsprvibo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2sjcubpsc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyodqllc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2gufbjrpx.html


<!-- 参考信息 -->