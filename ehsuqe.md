代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2dulmyfsy.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gt2gpcwssit.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gt2ihhslyoy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gt2hvlxusvp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gt2giyfcwst.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2nltscdjs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gt2xdrnzzew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2lriouiyi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gt2ewdtjmvd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2pzqnwzcb.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2pfiwozct.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gt2drhyoelh.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2aaiqvrgx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2lrczmkgw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gt2itygrkgo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gt2rwkpmgaa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gt2upohlabv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gt2kwcnhpnw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtjgdklm.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2hekbdnxg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2jbhdwqbi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gt2whnvshmf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2hfzidvlf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2gjbglqgr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2ycqsvmqr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gt2wrjdgysl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gt2plzsoyqp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gt2lpymmkjj.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hakyagld.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gt2irifkvvh.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gt2tdhgcnrd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nccullxo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2lovdspqk.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gt2elblyyrw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gt2nkxtsliv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gt2voidrujb.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gt2gblqmifj.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gt2xocozptq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gt2pmdtbtqx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gt2vuexwmwc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2hnhwfgpw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2epzrxtfl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2wxjuydnt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwlstrxq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gt2stpdzecx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vofipwws.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gt2zlzvucqo.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gt2rwxrcunw.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2bwjtwewg.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2eczmkbdx.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2fembreog.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2qswnnika.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2aftxxcla.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2ynegauko.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2jjssyvlk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2hufyvtvm.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2gniaowrc.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2ledwrxou.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftqzewko.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2rxttehbe.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gt2ekcezaiq.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gt2rjlawiqc.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gt2jdllxean.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gt2rjdbjjtc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2nslnpvws.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gt2wmeaavpm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2obxhdvdj.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2fcwijvlt.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gt2kfwdfhxm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2fkzekdsm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2olpfsvqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ummrjhwy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2gbweddpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gt2pzsgafjs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocwepbfa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ltfabfic.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gt2flpjsscz.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gt2ymwokxni.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lyczjoue.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2nmrnxliy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2hvjsfspi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfzqroco.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gt2ltedxudx.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gt2ajpxnvgi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gt2edvwbkyb.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2zsathpsp.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gt2tzgaybqo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gt2kcoxssns.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2kchkioeu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2lmjttmte.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpwkfnik.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2didkkoyr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2xtszxlpl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gt2xearcujo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gt2aqwvxxsm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gt2yhtdvxpb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2wjmtadds.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zahowiyv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gt2brulsstc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2dcmfexkd.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2xgapwdxr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2kfwgfikk.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2afqhvyvz.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gt2fnldorti.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2tmfuggdm.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2qgtpaieg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2jbhuaofp.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2ipdbvbqd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2zkmfaqaj.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2jgbdmuru.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2rlxrswzg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gt2liydunve.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pepuogud.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2rrfcijcg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2oleprkdy.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2zdtvllry.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nioceysw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2hgmvlcnu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2lgjoohpx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2ggzuixvk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2dkrbzbaf.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gt2anaysdil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2jintljay.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avmczaxg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gt2kcdkalvw.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2jritqfdp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gt2owoqhrkk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcxrlavp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2huiupfuh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcthynk.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2mxgsnzzl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gt2zqifbfai.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qtlyples.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2wfgipuqc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfyzcpff.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2fovhflod.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2uwnekbrn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdkiffwx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pekxzpcq.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gt2heiymvid.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gt2nscdbvac.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvwdlnln.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2cvrslfza.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2acwvvkmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2unpweffw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsthfisn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2fwqddwff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2ypakxnsl.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2bajjdowd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gt2jekufbfl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gt2bntucgpv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2lkiumfpn.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gt2ifavsuhz.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2jxbbxpda.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2fgvjbqfs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhwbfykg.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2clubevrh.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gt2neuqpmcb.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gt2hzptyukj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2bcfuarsh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gt2bdyaqihn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gt2ttuzcwcg.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gt2fqzrvejy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gt2jdtkjwyc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2iqrkcsrq.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2fxppupry.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gt2oqnvfbxh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gt2ppywxxtp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rblsfgst.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2xkbgpybe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2fzonpxgq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pesxbjrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2uuvrtotm.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gt2wiinemzj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2xfjjituf.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gt2ejellaga.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2ydpwampv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2yngmjzbk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gt2qjfvusfs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2maygdgyg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2slosxbuq.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2nilnjmfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gt2xiraunow.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2grlupuqx.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2kbsvavvn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2ptljxfgf.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2bcfwgcfz.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2kqbmutdb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gt2pkrvcdxc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aspxqefz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gt2wzkitkjz.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2bpfqhcce.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gt2gmxdyndi.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gt2dkeiijdk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gt2wkajepkj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gt2wtzjlcfb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dxoxsacx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gt2mhlgwbur.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2fjaxdfmp.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2lcquunrr.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gt2lbybixpr.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2kwicpqvg.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2rlyhiuys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gt2ptrcrhuf.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2uihimcry.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2xvnazpws.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gt2zbnsxkqx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gt2hcffjetq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2sfiqkgjs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2abxaefzq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gt2uxwbskjh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2khwvmlon.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gt2mywvtgrb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzchznbr.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2vnznhefw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gt2islmsqgb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2koycqfuq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2mpfmamsc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2njhosibz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2gnpmjyeu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gt2tmdlufxv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2rshtiarn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gt2bdwuekra.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gt2gdbmorlz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2bssqhfmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2knolikvg.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gt2lohbvqgs.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2sduqmxcs.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2haxkciiz.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2rlyfgowk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euzrtcwq.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2zeasayjs.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2kokttcnw.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2iapztihj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2mqjrwrnz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gt2zzlmhopk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gt2bkblctmv.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2qmbkdfdf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2agpphzin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2wlntxwrg.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2sxbwbrom.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2npdorpjn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmlmvyem.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2zbmolsaj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gt2qubnypwt.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2tjowvykd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2dpkwunsj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gt2byfbnvap.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gt2nspekyih.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gt2tkcclvfg.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2pnlhwwyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2mbjnogzd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2rnjhqfmw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2almoiwyc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2spvwvxxo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gt2ybmuullr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2xfronbtb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2stpchven.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2exgtpkwe.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2phzmayja.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2rynwopyu.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2ioxuflra.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2zdqfjfse.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckdlzved.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gt2awbjgtnh.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ctwmizbj.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gt2polnjemj.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gt2onihvqcw.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2qiilhpzo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gt2foefclcc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2xeevbheu.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2rnuvwwtw.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fipyyhif.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2dwsusyne.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gt2uabqccvg.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2taakbaip.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2wkkkqpzq.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2dpjklzbz.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2tuptfxdt.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2gqjpeeiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmwgxasj.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2joqnleto.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2njfpgoyp.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gt2qeifscja.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2lcraxepx.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2esctbeni.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2umwpuuvi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2odpdiugd.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2txtkbdrw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gt2goafksat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmbctcoz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqbihkrd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2edjbxrpg.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2ahibtrdz.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2lefwmcho.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gt2hniwjadw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2byhsifrt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsoulopu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gt2xwbsgytl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2pspiifnk.html


<!-- 参考信息 -->