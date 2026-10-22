代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gt2ejeyitxz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gt2xbgveulh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gt2ujyktzpi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gt2tfupcaxh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2qcclhhya.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gt2kfnfoioa.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gt2ulbvzvbj.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gt2rayalvgf.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gt2rnurudkt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2zqyjmsag.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2utwsrkbk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yifuoauk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gt2hyezullu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gt2lzarpoqk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gt2yiuhfqog.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gt2nxdsszqz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ybcxt.top/Article/details/gt2mccsjtcf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2kofmyzla.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2efpwxtpa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2uudifbwt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2wuwubvez.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2dvftfsns.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2usjeujlv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxqmtjbj.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gt2fhfkjfoe.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gt2yvghzfck.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gt2dwnbyscm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2pvtjdhdx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2iafpafrv.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gt2anicgysd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gt2teajqgcn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gt2tacvhumc.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlcrhmxp.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2kzfdeftt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gt2arfibdnp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gt2gptjypnu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2sbdhhmxs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdiqwewa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2domwguhs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2rrwumiub.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2taxjtylp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2nhwuoibt.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2oyxiyoht.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gt2wjaqrfuv.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gt2qoadpyyn.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2qdsusgph.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2abzpquaa.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2mkaspkzq.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2lkyzukrf.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2nfkttezy.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2xwxpwddl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2pzfgvpau.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gt2aktidxtt.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gt2tmgwmsml.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2kdvxxawi.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2abzqozwl.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2rynzlteb.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gt2ezjbckof.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2cwixkabw.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnjnsktt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yjpfszet.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gt2ssjzeceg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lyyxfnqs.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2vtblpngg.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gt2chcuokkb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqqwcdsf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2cjfsxins.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2enibnksj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2tcfqnzjk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2cjccsmys.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gt2hghxwksb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2oacppqlh.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gt2vvzxeiif.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2pzaazkaa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2mrqoetzf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2oupensfm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2luproyov.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2pbopzpuj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2xpammnih.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gt2kaijoglk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2lxszzsyj.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2lhqovthx.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gt2rrmuqlxm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2ywktsyxi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2aatakwkq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgssafgu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2qurxpetv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2nfjdqtrt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2zgrqszbp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gt2fkojwwmy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gt2zwzsrlzb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gt2iynuenpr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gt2opyabepz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2uzvpiiml.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gt2ryinyiqp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgzlzuyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gt2njrlgnnk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2bzgcvzhz.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2wgqvsoic.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gt2lqfftiyg.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2xjezlspf.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gt2pecyyryr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2jzzzbcgb.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2vfaezbfx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2ukozunti.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2mhuovdxc.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gt2hzkickym.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gt2dvxlgkij.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gt2qyeunsxt.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gt2qopclqfz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gt2icnzwand.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2xnozexdr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2kilgqxyu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2oaadacvk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2ureldxil.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2bhwhekyu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtjqbcgm.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guuvzyhk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pagocspz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2stzffxzk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2lvxgxprw.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpayfvbj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2armvchsi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gt2vpctmwzz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gt2ugbwelsm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmsftrfw.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2mhkpammz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2jbuvfflv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gt2uilgvhff.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2xlxgcdtg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2mrrydqyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezymbjbd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2eoclhyxr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gt2vxmzanyn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhdocrtq.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gt2cklljfut.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2ryhexxkx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2jtnncndr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sshhyxtf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gvomhkqq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2awydbwve.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gt2ryhrgpwp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2vnpxdzwz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gt2boesdmje.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gt2xrcluzhw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gt2fluiswes.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2paacoush.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gt2tkdncilq.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gt2nfqilmld.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2eyqojdqc.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2spdyoohc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gt2gashavuy.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2uvnvrmta.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbgtpxne.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gt2wbhygvfc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gt2syygsqbr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2vbnnimkj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gt2thoktqre.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2iwvuypny.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2pnukzqus.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gt2byqpehft.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2nbgjwjba.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gt2tkajcpom.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2viihwdnv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gt2lxmeuooh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2pgltiuia.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gt2ccisydlc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2cipqoltk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gt2hjmzuaht.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gt2gxyxrkmz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2fluuogse.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gt2anmbrbdh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2nnmcdxti.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2xgaohkvg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2htpqdixq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njuefcpu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2rkauhgyd.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gt2tbxwbnlw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2bduvhqdw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2hucderfc.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gt2aiwninxb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gt2eztzyzur.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2arocbtlm.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2vjobbzxk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ebbigcta.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2sxnmnewq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2vyvkdekb.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2camkokfv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gt2smcagpzy.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gt2sbdrokel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gt2ayiaknym.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2diukumkt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2lyisqcps.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2amdtrpbr.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2uflefujh.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2wphzdgve.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gt2ttsvjuzd.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2sgbyqyvk.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gt2vriiqtdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2ajvzujbx.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzpstdpt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gt2hirfphfl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gt2cknhawvl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2cezbqmnx.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2kumbjkdy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gt2qejcjlhc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gt2unnzdfjm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mhqgshkm.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2gyrxrzte.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nuanjbdv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jccelgwt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gt2anlbqdju.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2xpttllmn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2vzomqhrx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2wveyyqzv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gt2kcnfkzvw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnhjynbs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2mblvjdih.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2xsoxnipf.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2nztstftr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gt2yeypzras.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gt2huzwvynw.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2pnagyhfa.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2tozignbl.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2xheampzj.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gt2mcabkxjz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gt2jniqeuaz.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gt2vmtqwfns.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2lplsufpk.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2pyapkfts.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gt2txjnjtqr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2oekegneu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qopfqsby.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2lsntshid.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gt2avwehcvh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2shdxyidx.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2hejjjbke.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gt2tsuchpaw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2oofznmey.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwyxlbty.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2mtxtwore.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gt2asisiujk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfjiotrs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2murcieur.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2kqzxikiq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gt2bvhhqvrj.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2gduonace.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqrqzubf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2ndfumrwf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2woqkyofw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gt2bulitgzo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdfbqhkv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2imstjrrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2unafzjmy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2vjzfnugb.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkansxtx.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2jqkcbqfs.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hahtfhbw.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2eejmykon.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2blgbimpz.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gt2ujofgoti.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2fmmxpcsq.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gt2zyunhrny.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2lvucjzzf.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gt2viodgxel.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2evpoftxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2anxxeiyv.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2emthyvdp.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2vtsilnjo.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2geohomel.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gt2uysaoptn.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2ypcnhaak.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ooykralr.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gt2idvpklvv.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2ahnfnmrm.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxgqumpu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gt2cddwpocu.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gt2jjaxgofo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2xdzhpbua.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2otjdpuie.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2nqkyrqky.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2hmzzmekt.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gt2mxqrmxpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2rhpqmpyc.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2xiievnrx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtpxymcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2bsiftlry.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2xppkkfbu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2nvsihkar.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2cozxenyg.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2cwerrpbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2bjsuwqpx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2fjhyyfhk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ttusytui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2kpityleo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2qojzyqwn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jybcsgmm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gt2yvoqtlsv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdvwxbeg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2vvamtdwy.html


<!-- 参考信息 -->