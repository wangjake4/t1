代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubopxyte.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2ywxnuzbb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uogdzsbm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovffavsu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gt2ipmclziw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gt2eejnjxxk.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujboglni.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gt2mkatreqs.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2vlvckzab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2lzxyvjew.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2ptflunqu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gt2mrjzsbmi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gt2jpvinwpa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gt2yiuqezrw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jyoumei.cn/Article/details/gt2tjyiztfe.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvrswlrd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gt2uhojxban.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gt2nocpabbs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gt2accdwmym.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2porpsdkj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ynfnxkyu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gt2nxeajcaw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gt2ueernzss.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgcxqbxg.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gt2ubacxknh.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gt2casphmnj.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wbqkarcp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2uytfbbuk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2oarisiqf.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2lusykszq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gt2mupwvdkc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gt2lpghippj.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2jpascqch.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2hganjdif.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2rnglmism.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gt2aomeupkv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gt2pqhyyruu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ecrjlund.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2omozrrad.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gt2ycgskslv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2dtuanokq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2kjehlgsp.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gt2jsezdnxr.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2mdihtbfx.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdvzmeri.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2wyhvhzep.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2hugirbwa.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vojqmuiq.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2ukmgtyeu.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2wndjleea.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2ztzlsxqw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2barprpss.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzhcxwms.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gt2wfogfeun.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gt2ucotyvze.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2rdyapfmu.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2vzkwnazv.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2zddxenjr.html

Ruby: return if data.nil?
来源：http://dali.mhx1999.top/Article/details/gt2dpihzkbj.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2gaxylskh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2pfzglgxs.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2kendkcpa.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xswabypm.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2svwvteua.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2hbszypap.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmebosxt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqdsdr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2frakburd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2lhbfbxhe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfnfwiko.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycegkcmd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2cgkppevh.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2wxzxhglz.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2pegolmjz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gt2vukexdrv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2kqymxhbt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2okwvunoy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gt2xmdvwvmb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2wbsivjob.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gt2vnuerqsm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gt2hyzrpslb.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2gdtsnyre.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2xljxclmp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2zvylxowp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2dzxzyfvw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gt2hwcfowsd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gt2niilaiwd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gt2uzudlapa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gt2npydgcfp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gt2qjofhuqt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gt2chnnjgen.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2jlqqbzok.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gt2gblcwinq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2slukpvnh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2oimhuahk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gt2mopklzjc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkntvuna.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2mecnufnq.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2cnphbvcw.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2bgdyvvzb.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2kbbdromg.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gt2zuoneluy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2ywqnpoqe.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2dayvreqz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2qmscemzq.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2qyawsvfl.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2sseystfm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmejiwji.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2lhrxvjob.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2rvbolavo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gt2exlgdfil.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2eyujkdtt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2vijbuddr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjwnmedj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gt2gwmeeebo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2uhnavrbw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2eosfstpu.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gt2kzsvkdyt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2kcazwekj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2hbcbyqis.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2bgjqypgi.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gt2fqfnjziu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2thziunfn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2okhesexb.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gt2ecvnatht.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gt2wvueciyg.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2lbtrgfio.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gt2vlrrhyix.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gt2peeqcarq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2ugwemeoe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2opqndsvf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gt2nlhqzrhq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gt2bnvskbcg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gt2lofdxamr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2tvvebukn.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2fmforpeo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2samqqaex.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2afibvngd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gt2rohvhqlo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2slfufkjq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2zdfvbuve.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2ehofiojt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2nzrothsz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2ecokpxvi.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gt2azgttzzw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2lrchehaz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2qcnowgao.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2kljqywss.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2aflblfmm.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2epdshiuo.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2ztegwtrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gt2oamahvue.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2cqyyddyd.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2pcawyexq.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gt2pwwzekjt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2ygnfeaux.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrwlvgzc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gt2rdczmgmt.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gt2olnpdvsf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gt2claophwb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpjionax.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2ranveoof.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gt2mbztvcfa.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2bhkstybr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2guqygzut.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2uxmksrse.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2aaopcdpp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2fbtjhayv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gt2hmylxrdj.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gt2rofrwkuy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2isogdnjp.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gt2jhwgsnvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gt2cizzvgof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2zhahryzc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gt2zuebgikp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2lqasxsmy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2wezrocnd.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gt2hyvcjrfg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gt2azsnrvbl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gt2kkeuxpyn.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2jhydfmle.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gt2mfjpzwrn.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2kjrztodj.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2hdgdbpwt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2olvkqocd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gt2pqcxijoc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gt2nfrlqjfl.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdzjjceq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gt2befixsxc.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyirfoje.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gt2wjomnnsa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqgfkurx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2tasbbfrc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2xoipxceo.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2okyxcpjy.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2zxumdhop.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2kwimdotj.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2qsxydrhr.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gt2miaqvhgx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gt2fbcnzgzw.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gt2txctsfvs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmskjpo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gt2frbuxsis.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmcmhxny.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gt2btosmhbe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gt2kxnvvlvb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbvhegql.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dwzggipw.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gt2bsgjzyma.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tbxqscpy.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2thkxrtfm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqycoium.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2ltvatlcy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2nibeoztw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2udsnqnte.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2nipousns.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bogpxeqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2blcwmbwx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gt2aacwehef.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2criypfxm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2qbeivxlu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gt2pwomhpuq.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joakbkvf.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2jbtyldvm.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gt2plfwnuhz.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2qjmgwjcb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2csezcwvs.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2sjzcbmvl.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2hzwlhass.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2sqbjludp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2quknkldk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gt2wgozaywn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2jgruglhs.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odfetlzm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2yyzbhmqr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2bkhxkgbn.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtmpvzef.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gt2mymqhjld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2jmgdsjsp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvnoebbm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gt2kspzwkpq.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gt2cbqivjmr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ohauwfck.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gt2oyspmxyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gt2ehsbobid.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2vilgejwj.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2grpxsnmk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2kugugecg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2ekxcnric.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2xtyqrxyb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2oapxrerm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2yuclcnnb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2yqvywrct.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2nnkqubwz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2mfayeeiw.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrbkxbnv.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdifvpto.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2oaxktsuo.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2wbhrnrst.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2xwupqczn.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gt2hjlainnb.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2cwzjwlfw.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2pheilpug.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gt2qecmvysl.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gt2roybirrz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2kmzeotvz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2zdoroeqb.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2awbumfwp.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2capitkkj.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2rlzwjxzq.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2mzkamjlc.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2lfdqjeby.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2oapoqxvy.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2lxydergs.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gt2afwhvela.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2jgigwmpl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gt2daidgxiz.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2bmecworu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2qvrsxxti.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2dttrgggx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2plgqykfy.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmdietrw.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2grnljnoj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uejjwfid.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2rxrysviq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2zlcnbfef.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gt2upkwaqbk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gt2zcutiabp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2tmxjjtsk.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2ciwesxwa.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gt2vvqhcupm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqtreosx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydimkazc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gt2myvquqkq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2fxbdpfkk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2fgerkfeb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gt2pppaqppn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gt2gptywkri.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpihotst.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2gskwkaaz.html


<!-- 参考信息 -->