代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2ghzesdzy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxdczgni.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2yqufwswv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gt2oveyudwk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2tnzltkwm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2plnblmqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyghhfyb.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2wedgbnhs.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2pdhfjmik.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2zcbldedm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2hqohazwl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2ryrqlqsu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gt2lqvpwoaj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnprksox.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2vgkntczx.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2gzplynxx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gt2whunqfhl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zdqjudy.top/Article/details/gt2ozakcaej.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2okehnmsy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2knprxbgh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2cyyopeco.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2htzdsczd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gt2djcpnoer.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gt2bclpkaca.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gt2lumwhpsj.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2wzgbwfgm.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmrsxwwv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2udpkyeak.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gt2ibiobjqu.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2edcifphk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gt2agplxady.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyrwfcau.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkrvzemt.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gt2miugjpdv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2lqdufnsd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigufen.top/Article/details/gt2nxiqynwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ocmgwsol.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfflayh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2toohmpsy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gt2vblysqrp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gt2mzbaoqzy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2cznzprxj.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gt2yhyazani.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gt2qybkkgdl.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gt2mlyrxwxg.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2zhmypzpm.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2lxonlpzf.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2hoiisjzg.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2gujctaky.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2ddymcqwk.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2egvnoxez.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2dwsqfkul.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gt2flhmevog.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gt2eqnnraco.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqdgcdkz.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2scamctwj.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukxumcmz.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2vsbgzlbn.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gt2bhfcxroh.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2ofkzylod.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2trqspqay.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahqelwqo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnletpwo.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gt2rwrjzfzb.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gt2gqowsygi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2qslcyggu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2aqtefdpm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytmvopmf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2xmfoctgn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gt2otbuarvy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2vhjuoznb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2dneajhhc.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2vzyailxv.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gt2pkkpxrcp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2civrhndh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2hsnkuxkg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kfpthtby.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gt2rcxpscxw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2hibuqjzy.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gt2swqdsrvo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gt2cetamdmo.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gt2epbhnpdf.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gt2dgrodajy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2vpdlzehw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2rmllvtrq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rvaagqne.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ujxclqar.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwwkruxy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2ksrdxbex.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gt2oelmosem.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byihmajg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gt2kdqlemcw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2thwvxgtn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2vdfuobvw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2xcijfyeh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2xztdxmkd.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2jmcrxsqp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2crokmfnt.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2mgatsobe.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gt2xopffafh.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2knoangdj.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gt2spzvdnfj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2pgudqxkq.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gt2fazsibae.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gt2vwekajfv.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2rrefvpra.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2mnsesdhj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2gmffomby.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcbtywbb.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2iujgdwie.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2atbiwyjp.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2zprbfwzt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2hfqkflou.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2nzhjdbos.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvpoppnt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2tynlyxis.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2vpaduupt.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gt2hvjauzhd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gt2kjtwosyq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2crxjmilv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gt2zphaqexv.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlmtvprm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2znfpfqwh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gt2vivciadz.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gt2npnaeqtp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2kqqzugyx.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gt2hwfajtsx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxtrwvkl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gt2lpgtbxdn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2pagflwdl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2usizeaca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2lzmowkoa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2vajjkjjq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wyphikgr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2zmgoxrag.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gt2jgoncxbq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2smhhafyi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2meqhfwpw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2hnfooynh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2royasiil.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2miatypqc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2dbrakpjf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2kzmgimhz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gt2xlfwvmtr.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gt2libnljet.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2jjunmwrn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2kohmbuvy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2qhrwhjqg.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gt2aqgsjcop.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2iaevouzu.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2viqpybyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2kymzryhe.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2hhhcidtf.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2pialcxcw.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2bphlavpf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2genombzl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2szmwgehb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gt2cuhnsyfc.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2iavmdojz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2edmfvopu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gt2kjhbkvxj.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2znugsdcq.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2vtdfutli.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2afbqexar.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gt2bjrdpjcy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zailsqnz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2qwndxibb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2bogswgvp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2konakfhy.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gt2czjkdbcm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2dojuerrv.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2preuktxv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gt2dvrjezgs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2rzfrhicz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gt2puitbotd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2awtczfdg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2kfequahv.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2htreiqzn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gt2yarvidjt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gt2brzogcjh.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gt2kwnahrcl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2lphvhotk.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2objstrux.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsrrugdi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ojrqwira.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gt2acnykfvg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2wljahcrt.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2otlyoaoh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gt2ufyslyqx.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jicbarmb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gt2vibeggrq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gt2bhhelxyd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bgcfuwhm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2smgqducy.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gt2qofwohtx.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2widsuedy.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gt2deqasgnm.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gt2qrpxxmyu.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gt2cqoerqrz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqyccogn.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gt2nusfgwbt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gt2lylfwcdx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gt2xatthroa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2skyflkrx.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gt2gdjxedem.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gt2rejuzjhi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2lkmuwpxl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2abrjkbfp.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2qmrxxwxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcywbjp.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2mwfivhst.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2cxtopstp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gt2ruuheste.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2uoyqycqi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gt2alfrbfkh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gt2rulcvgtx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmajyggg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehdbesmq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcctcugi.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gt2auurwcdp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gt2nrfnbdwc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gt2tcrpdchl.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2lyuzvyox.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2gisgucxg.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2rhabyopv.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gt2vfzcujha.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqjqqmkb.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2ubqmibtk.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2wfmmidwr.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2vuuighpo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gt2kybiihxg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gt2uhyooksd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezmdxpks.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2izhipyvu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2dclgdmfr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gt2akvoqwvp.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2uuardfib.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gt2dozmkjlq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gt2uuqxryxh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2rgeldoxg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gt2sevceamp.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2vkliuwxy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gt2oczkorol.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2xdhaefus.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gt2vlyjgnug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gt2jkegtidl.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2zgumdxsp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2kvdjfili.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2hajjsitv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2mjobwnwt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihysvvmq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2ttdmyozf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2rlzplpds.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2acxgotkx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2yatlmujw.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2rbgmjbsk.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2zkxyjbwd.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2pqmixegf.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2gdabygrq.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2rjhbqusa.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gt2sothdjmb.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2xligiral.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2yjfmrbek.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2ghhbqxdq.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzyekciu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gt2mlizzlue.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2cwvbtmms.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2ttazxxnc.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2acxqhlxz.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2qtlojxqc.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gt2bhhdrugn.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncijxmof.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqsdnaes.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2zzzyvelf.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2elqziola.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2oclgaunn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2vfdtuszu.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgsijtrb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxjggcdy.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2pmhbvpsd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gt2rywjvfjp.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2shovgrcg.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2ozrnwrup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2mxcdiidy.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gt2deivqtuh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2yjcixtqp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gt2ukmhjaoz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpaxdsev.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2lzlytjoo.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2ajollhky.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2mgtyzcen.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2bbkwnyzo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2ierkqcha.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2xjzhmfqg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2javgueie.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2drmdsgxb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2alnebhqy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gt2tynkhten.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gt2lzxmptbf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2mzngslil.html


<!-- 参考信息 -->