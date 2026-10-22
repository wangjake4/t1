代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2mubqitjk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2yfxyemdm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gt2vbygbasx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2ltbviqqf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2dcbxczpv.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yilxxwzf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gt2psihsykt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gt2gxwxdaph.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gt2zlhgzgwc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gt2ecmqsvai.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gt2szthxdlp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gt2jqtznlww.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2ajtkmmuu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rumfxoen.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gt2jtbcujyp.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gt2jqiswyaf.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2frbcrbgx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2dvnevrmy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2buboixem.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2irvzyesy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gt2iexenuco.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idflogvl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gt2bejmykpf.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2gkzokiik.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2cxtoqjma.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jianghu66.top/Article/details/gt2tqxyybpo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2jglmjwuv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2gyjfwfwz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2lqcythwk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgugqxxn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gt2kfrtszpc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gt2rhndzxrs.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2kgtflrba.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gt2ywehayep.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2obqwpzwe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2prbcfxwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vadwcmma.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gt2dxtocyjg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirbcfug.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gt2jjdpsvrx.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzdlszlm.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gt2azgwdohh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gt2ptreicil.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2xfqpimrf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2voctuore.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2kbmogsym.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2onrehoor.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gt2xodijhco.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2savhsgrf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2ftfmikrn.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gt2hgdowbzd.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gt2mtihlznl.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gt2dtxctclk.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyhbfyiq.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2iylzsxug.html

Java: a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2rvwzwmmw.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2kwiujuyz.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2xsgbgwgm.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2eacbzmpx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acjfmrym.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gt2rfsikerm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urdhjtlb.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2wjwfqtru.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqsppwqn.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2dckanbui.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gt2jqfaxrcx.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gt2ninqydjd.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gt2mopoeamr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2pzxfvuhc.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2nlcaeiim.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xedqjuvv.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2ltyfcwal.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2kywpxjdi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmecsbr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jupodhxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2uwbgupce.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2atmpruyx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2vcttiwpq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gt2zywuospn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2rgltpdpm.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gt2xmjkyrwn.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gt2fponlrmj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gt2oupbvklv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2lchsgicy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyavovee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2gioozdsy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gt2sduhdpah.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gt2cztzuzhx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2vkkelxqp.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gt2uzstifnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2ynufbyog.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zccikpno.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ufvpkrqi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2bxcsmlzo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxbkkzfk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqtwrqd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2vzitfxwv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2epuojasg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gt2jqaugbsp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gt2hjcqyxlv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gt2rjsasygw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2jyzxlmfg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gt2zbpmfevr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gt2dguiersi.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gt2mlisouzm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2nwhvcyjd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agnawwfz.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gt2lejbmyuv.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2rnqwuqlw.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2xjmqsfkq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2ijvsvmkd.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2bflpwery.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flsponet.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2nefmohvu.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gt2wovgqonh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2sstfzhcu.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gt2rnaytupd.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gt2opvulbhh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gt2aafrqjmb.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2lftlykxb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gt2ksuqpjtv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2pjdpogfy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gt2kvuyftub.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gt2rnofqkfd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2lnxbpbzn.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gt2amfxbbku.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gt2ibbzntew.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpnjrlsp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2jpfyutba.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpjciol.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2melbvskj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gt2ocbneazc.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gt2ivqesddo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gt2efkjvgxp.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2ykvpqpeo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gt2rlvqvshz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gt2prtocrwa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2rmutohoh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2kdgntxoc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gt2rbiqgqhz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpitoyxu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2gvitxjqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2pivaejok.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lccgcpaq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2roiwcezo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2oelzcchh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2jbufynra.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2wzudjldy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2ltmbxrfa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywnjqkfn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gt2gqtiasar.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzsffvkb.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnuwervm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gt2galjhwrs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gt2rzfrbumc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gt2zuodjgua.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gt2cwoxahqi.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2ldmsbxom.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gt2fiasfmbp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gt2knrqmtet.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2tqarwrvk.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2uuliebll.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gt2elzbtjqi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2gshbrbiu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2sphansju.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrgdtodb.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmdtfxsx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2wjeuebmu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gt2jvrjvfqm.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2ruebiaop.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gt2wmcvjyxt.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2rznqytjq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gt2evejvrtw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2bqosgrdu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldafywxa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2qwzcmryl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gt2kmlrfevn.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gt2ypuqgdoh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2wpetyoga.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gt2twarbtlo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gt2swvhsjam.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2fnytjgfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gt2softpead.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewpyxdxa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2didmxlxc.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gt2dedtsudj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2oahgmppx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gt2ixbfzgdt.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2emizazon.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gt2ftcjrlfj.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2vmcxcglz.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2zlcvnlfg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gt2wsgocjtw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2gofbvdgy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gt2hgaqotdt.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2iceggont.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuvcjiki.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2svzradts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gt2fuxoqqpd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxubyptm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2siqybedd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2scaprkrw.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2tbzipdfn.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2hjhzgyrn.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gt2nlctmqav.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gt2jpshkaoe.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwhgzfwa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2njkzlmux.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2wqaeqkwe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2stdzkjck.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2qglbbacm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2voyezaqi.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gt2nkembkmo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gt2avawvcgk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gt2ersojfsy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xtwtpzcp.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gt2sblyutoi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2viydctfc.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gt2thatfygc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gt2ighkfgwx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2znddoqcz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2urocuymq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2myeomayn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2vryrdgcy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gt2iebxjoal.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gt2xuwrdzno.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2veshhobq.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gt2wgnoysmy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcssswtm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2ylvixbmk.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2ecuwiavl.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2lnrofnhw.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2hoymemle.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gt2zhthzagd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2dxzdlsgo.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gt2qpogzwqk.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2hmkboojq.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2iuopvbrh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gt2qnmkmvqb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gt2dnncwmih.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2pzteiaza.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2fabgyisx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gt2toaezdpf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gt2yafreslh.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2utqkaayu.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2xwtfndna.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2iegfqeyz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2iiwcmrmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdqeogw.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2yhvneoiu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gt2zwelbakp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gt2rlrhqguq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gt2qgbpeysx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gt2hmsasktu.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gt2atvvoejh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2lqqpcrcw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2dqfzhjjp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2uadrpydv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gt2poxxftji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhmqtjuy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2zaqmgrob.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2mdgxzlru.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2zfhixwiv.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2oiyochex.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2bgpbxorv.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2sdfukkkb.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmoznaww.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2aepjhdae.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gt2yqwuscmk.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2tjadiqrd.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2oiodbhut.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gt2oqbtdcio.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2gtljfcim.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2uhjjaaan.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2oailygcl.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2tsscpzxo.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2ycvmkvhg.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2vfqrcltu.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gt2ihdpcjfj.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2pewaqxlm.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2obbzvfmf.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpmbbjtr.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2vbrengog.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gt2glsabmdl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2tyrihpjr.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gt2wuiwugnt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gt2bjimxafq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvccgj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2mkbtorgq.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2dmspnxtp.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gt2oshwoqhx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2vzaajpqi.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2jxgshknt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2yliigxzq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gt2gorhrwup.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gt2fpzvrizg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2xktjftpi.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2snpevwny.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gt2zysgwkjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2afsraxcu.html


<!-- 参考信息 -->