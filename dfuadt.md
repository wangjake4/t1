代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gt2rqehktdd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2sqevwqcs.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gt2rgtfxbow.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gt2zhokggxv.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gt2qxonvrmp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quwlmqbn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2daaksbdo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2keiyqbtr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2jipkitin.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2ppqfgher.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gt2mjfgpnns.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gt2vqluujud.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2yrrlynxq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqkcgvld.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2qfpdmglm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2micafyhg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gt2doxukety.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uagcwvtr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2aawfsmuy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gt2jkwqlwun.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gt2fdcplbpo.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwewffnw.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gt2drmmcoov.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ilfscbxp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2xhqykxlr.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adkqpsyw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gt2ptnzqcoc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gt2blmnyqdn.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2vlwveswy.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gt2qfarpqoq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gt2xgwoaetd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihavdhth.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqvkqzuq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2jlrsukmw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2bnfmxzyu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2rmdygwnp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2wsvdpnhl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtemcund.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gt2toetiggq.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gt2dbuapzam.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gt2exouwkfy.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2sorewoit.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2hbllxccg.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2caxdtkja.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2zlytujam.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2ruzijsyb.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2ewsusqkx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2xlmzqnmv.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gt2wnbdtqam.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gt2upvtqrkh.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aenvalye.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2rfrziggl.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2mcovsqwk.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2zykpiitf.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2xetzitiy.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2khidrubn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tzfvbuwx.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qukvcmab.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2htlfuwah.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2dvmkppye.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gt2wlybhrej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtofekac.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2akhipiyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqcdztpf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2fjtvpxwz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2mmkggygb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qvhijlxf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2myddciet.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gt2xskwfpbw.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2vrvtfdor.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2okuezsvs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2rbutpzwt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2ewywzeew.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2byjblzhs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2edtlvcsc.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gt2xjfccuks.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gt2zvzyqfdr.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjpewzmq.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gt2hkuxnogx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gt2ssriigug.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2peaeqydb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2dblgngqg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gt2wrcoraws.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2ddpyrpgo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gt2oxggaecf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2xmzltxlr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2oompaopy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gt2bzrezefl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2reaudlvl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qpvqbivx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2yjrhtyri.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gt2cjcygxep.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gt2hcdbtxnh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2slkzgewg.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydkerbwr.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2wshwckgs.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrsmlmoz.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gt2uzuuxphm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2irykuzme.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2tffqzfbm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gt2ekolqoyv.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2sxjemtdr.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2xiqnhima.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gt2xizhextf.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gt2jvorqsej.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gt2epcpxenz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gt2okeovajs.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2ebfveyxn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2egeuwlsr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gt2hmmgjaom.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkhuuhqk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gt2plnawkum.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ndlhoipn.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2sktjjlcn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gt2lwazgzjm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gt2gktotsnz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2jvafpasu.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2pynlnbyo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ytabtfhg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2tcjdyxiy.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gt2lkluezjw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gt2kduiiqft.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2xbxoezqi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gt2wrvuopgx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gt2btmkyzmf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2yckjeeow.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2urrsqiia.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gt2fcglqwrf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gt2dvqdecgg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gt2czxjjeyu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbuwtgfh.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2aygfpofa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2lthtsudv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2obuxudqf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2rnkfsjdk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2ejrmtlpk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vujyjbhf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gt2bsldizzy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gt2qbiomtml.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2etnvyqwk.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpkfspwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2xbawstup.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gt2vlaboole.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gt2cjowzmio.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2ulyhfwmi.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2hbqsnruj.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dripjqni.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gt2kfzupcuk.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2killuqfc.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gt2oeziubjk.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2hoabbhbt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gt2bdkgwxpc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2smjbqrjg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gt2sekccdow.html

Java: import java.util.List;
来源：http://dali.nwbrower.top/Article/details/gt2rnltybah.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2cfjzkfkh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gt2sxlpters.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gt2qvcljskz.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gt2qndsuiku.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2rselnsiv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2mgvlhwgh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2rfozbikq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2cfcvzboq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2tdmyypct.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2yphemlbb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2qvrkwsdr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gt2rhmjbmcl.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gt2iuhueied.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2tevefgpw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noicyhtg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2scrwbjrd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykoxtqii.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2gtkjzmba.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2nnzpxwij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gt2rssbjmvv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2mjysejwx.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtwayjfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gt2dewdegvn.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2bahjmyyw.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2tonuwbrs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2cnhlvnsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gt2kwghyoxq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2vmhnjsea.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2akauuslw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2lnbjxouh.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2uximzfbu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gt2halmdwuj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gt2jughrplr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gt2teesyhez.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gt2uosbnjiz.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2aiqlewcj.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2tcsdcpvu.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gt2sovkdjoe.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gt2mdykoblb.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gt2micnyeuz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gt2gkvdveam.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2yubjxeiu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2obxbsvrw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2gzrgjawl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuwfjrdm.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2ioxnpsdb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gt2srjwtzgf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gt2gfsgcorh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2noauvdws.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2bowfqvzk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2slwedxcg.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2vnerpiev.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gt2tfpdcnce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2zivhicuj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gt2nfzltajb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gt2vwndnbgb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2lbdvylvr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gt2lbldvkyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gt2izafsrjl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gt2xdraofzs.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2aseojpnj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2tczhtuji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gt2lztgeiyo.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2zixblyxa.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gt2jokxgkmc.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzhcatkh.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gt2krmizpky.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gt2pbwshcjg.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2ijcxiwwf.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gt2furlhvjh.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2rkjkectw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2ikvxgckt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gt2dmuzxwwd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2jcwzudxf.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ygdgjuur.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gt2sutfcufr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2ksdiqetu.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2szllftep.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gt2eypheogx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gt2moqbahlc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdqskcsv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2adkhsjvo.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccjdcaof.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gt2rmxldwkd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2oojyutez.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gt2wufvqamr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gt2kjrpdals.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gt2hqhtxhgm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2dnhjqalp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2udyfjday.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2zyqevemw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2mzwnpiub.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2iebfnvep.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2efndzwnk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2bdcvoyns.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2aqxefecl.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2hxhjxgmm.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2xppipkjo.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2wrfdtqmd.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2tljgapte.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2beozyshv.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2dmqavxlz.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2hshpctne.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgmrfslo.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gt2bwgupdtp.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2hyoqoqys.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gt2gkjslhjx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2hcxdisxm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2knlcmuta.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2bosigxee.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2kjauuiws.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2ebbyrwiw.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gt2zatfdtyx.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2qdzmjycc.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gt2tzffjtcw.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gt2wxldowwp.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2nrzflmns.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2xywvjhyx.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gt2czxznzza.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlwdkuon.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2csjhokgi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2mduaxfbz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2lfbuezlz.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gt2khccwqrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2bwaarhfr.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gt2bwkdskki.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gt2sscbbppv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gt2xvjqpvue.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2muyukmsj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2ewpvpzwq.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2rbqcnlot.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gt2rexuxboz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2dcmnpifx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gt2tjhbjvdx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2thnncwqq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2wdkfucco.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2ndpekcxh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gt2eqxgynry.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gt2ehijokpf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gt2uxbwdptc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2ptyvbpdl.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gt2icxmxrqq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2udgybwig.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2bbljdqls.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gt2tgwbvahc.html


<!-- 参考信息 -->