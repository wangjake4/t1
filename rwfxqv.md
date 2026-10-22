代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2npshvfed.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rupkkuvg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gocckjii.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gt2rvvvkoco.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2vgfpjfde.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gt2oviqbaoq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2sakdooib.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gt2lffqhrkk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gt2yyudbtuy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dphyavbs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2bklvxtfn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gt2nbxdbqzf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gt2yqbpphtl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gt2votxacbe.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2iveyovsm.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ceoqfyxo.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gt2aruufvak.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2kzthzrqe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2kiwagqbq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gt2nprabugc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gt2yeplvuaf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2hthdpstk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2xdhemvbr.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gt2rurifpqf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gt2zsuywacv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdvuihrw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2hbccriou.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzcxtppv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2vyotnfsd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gt2wrgkhqle.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gt2eczeraaw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2wekjdthy.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2vctxxjjf.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gt2wmkwmiqo.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gt2nwdwlzkx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2wfcgdqds.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2qwnzzomn.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gt2jlnzqwqo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gt2zbsseycr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gt2wxlhrhia.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2kcqcpkre.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gt2xkbcucos.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2jdekvxqq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2laoywoxa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2dnnywfnp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2oucbiujb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btpokvhd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkuxbass.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2llfgsbii.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2gdhcvnlp.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmazieeu.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2kgjxyrhk.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gt2ojwexsms.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2putfhjrm.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2oogklefw.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2vdgmvchw.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2aobriwtd.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2awesxnao.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2oljhrjgw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjrrajpz.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gt2btzwwynv.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2fuvganul.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2linwayth.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2jojvhmgx.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2wwjqgrjy.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2askejtvk.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gt2gjrwykpf.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtvwxlhx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vxtfmetz.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gt2enjmejov.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tnbtodee.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2kzwozxqz.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gt2vwbqiybc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jewalrnh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2ubcgavxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2lxrtbfla.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2zefbgrqc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2reezqljc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2bpjpeyxn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2leueifzp.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2ycucizes.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2ucxlnrwq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2fmwysrgm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2egdrimgj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ufyajbgj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gt2jjoewyeg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2ondkkkrd.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2hnbhkjub.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2atbvymov.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gt2cxamzhoh.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtwzgzva.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2xrxweslh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ctgvrcmi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2vtgpyesb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2urwusowi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gt2vbsxspry.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gt2feqetbfp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2mqzgccbe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gt2nzbqisyy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2hfapscla.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gt2zglhkaan.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uouigqbw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2bxdjtexk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gt2bwagcrcy.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2hhfyfhvy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2amtayuwf.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2vybiauog.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gt2kqfymyku.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2vdniucxh.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gt2ubbanprp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2phpbinky.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2cpjgeruj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gt2uuxjhqsw.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rumtmpxh.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2enzrkkca.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2khupulqd.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2wnhsbqey.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gt2hpuhcepo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pawigaom.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2ypvjpwak.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2vyjttfny.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2owbqpchs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2vsmsnupv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2ytewidex.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2idszyuae.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lskdaezq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gt2alsbffus.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zadnbcfu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gt2kyasdmvd.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2vzkyjyzv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifmxkaph.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdjqfwno.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2tnwbcfmt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2angcefps.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2dnmygjsk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2oufdmouk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gt2uyfueaeu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2jjyyolyi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2mhwvbirw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gt2fntclqcb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gt2kkicfdvu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2qkhigwbc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2ovivfucx.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gt2ututiabg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gt2tmjqogkr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gt2evpwxqel.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnculdaa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2dwtpquwn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2ycllualr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gt2loeptfig.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gt2sgyobssi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gt2tprvzwjr.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gt2aogbqxaa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2kwmhinod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gt2vzhoeqnp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2pqsvxnxi.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gt2sbllbthi.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gt2tszbhdbm.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2nginiiwk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2sliaylcx.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2mkhlluef.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2tpmovtui.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2lagwidye.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gt2zovuxulo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2ybrshzsn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2amtrkkjk.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gt2jnhoftwo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxfznaiy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gt2oobgyqyp.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gt2fyaleaij.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gt2dlxigkag.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2ajfamjvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaiocrku.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2qahibrjj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2djbyulay.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2joqwjsvl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2udiafaks.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2xqmokaag.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2vuahgtcs.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2fovmmlbu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2tczskhuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fabfspks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2flpbporh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2quvciasd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2erlwglfs.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gt2blbpqzgq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gt2mnfbgbdo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gt2lsffzhfg.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2johbnjvn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gt2jwbbwped.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2vtosvtps.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2jscdkzka.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yirkfagp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrrirosf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrabcfqm.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2lbdwbbkz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2irbqfspj.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gt2tizyslik.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gt2pnombeye.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gt2jjyutzvp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qipcznwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2emoareur.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gt2gwacwcdm.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wckwdshj.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gt2zskdhgjd.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2lnqhxgps.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2hxhrdjly.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2nvmabemk.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gt2syhvwyhn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gt2mcrfuxaa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gt2rpeqyhbs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxrgzriy.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2wdrlsmrd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gt2rswskxxj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2noxboqwz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wydgpkur.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2ldqdosjp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghadaver.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2csumasnn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gt2mrbvctqe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2mnzkeibv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2nrwflbve.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2zxwumvgw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2zkgtpxan.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2mhfyjnxl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2ptfqeheq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2ydgobabs.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gt2ggqyzidx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gt2gahbwcue.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2ppgojfeg.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2wsfwrgtw.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2ojozmqhr.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2irxmunlo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilfiqwsx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2iiurmbmx.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2mdghixqa.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gt2hgkemeyl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2bjfwiydh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjjtqxfm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2tnwydfnr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2eczvjxcm.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfunjexx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gt2mzqespzw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqkaasmg.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2mcwsxrgf.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2kdwvlacw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2cuqwgztx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2wmqxpwzr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gt2nqafxtmo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2tcvdqrrx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekmbtesw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdxymxjf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2sxirqawj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gt2afiwmskg.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2cnaclyks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2wpwaexuv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2czbyplca.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2ckudmmrb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2rtvddecu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2zlryzywa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2wsobmvbc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2ttfrvysf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2njekytjx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2coxcetwj.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2neozxeuh.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2skajoyur.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gt2eadjvrqo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqbsbsj.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gt2yfqldhhv.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2lgwoeiup.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2mjgxqtqu.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gt2dldpvott.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2jifbugah.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2xskcfamd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2zgdocktu.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2kzwicodn.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2yfjioyhx.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzzgpdaf.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpclzydn.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwbtfdpw.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2myqrieza.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gt2rlksjzgy.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gt2utktswvt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xibcorca.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2fzykkpwl.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2sionzvje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2iuehadfh.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2zklgnkxi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2hbpzuqlh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2yxjbfdqt.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gt2xjyxkznd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2kcpxohlp.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2lzjsxopw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gt2ugmgmchx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2eocnnyej.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2kslhwfwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epyhbekb.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2xhddsyuf.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2tygobgoh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gt2rorxmkmv.html


<!-- 参考信息 -->