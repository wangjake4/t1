代发 wailian999

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gt2slqaelvz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gt2xisjjwve.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2fdwyqcwu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hslaekno.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2rdtfsbva.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luytxkcm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2irgfibdp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gt2pfrjzbxt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2vrmibaoq.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gt2kahwitnl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gt2ylkdfbaw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gt2pyjjpvwa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gt2wmtkneto.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2prgkcdpi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2osohwsbd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gt2frxdzzzx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gt2azrgapru.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2ebztjzjc.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gt2clsjcqxe.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gt2kcyclchz.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nssvjtjz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gt2drsjahck.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2haiajqaz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gt2qkznmrxz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2tkogjksr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2aggzhzov.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2awtrqiyn.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gt2qmevnbuo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gt2tmndisfy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gt2ioqiimey.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2snhmjfnr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2qpdcebwf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2tqbubxnk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gt2wjltsauh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2dduzewsm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqwkqsqg.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gt2hqfhvbyr.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gt2avlasunp.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfmrobpf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2giuspipz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2dmngijuj.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2asuudunc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2eqgsdkfl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2skvdovyv.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gt2maxabnuf.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gt2mqmxpmvy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gt2lbhtwfxa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2byghtaqb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2dfbdhllp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkwfnsbs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2azbmcklv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gt2fcdqjmpj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ookdnclx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbaywtz.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2myjqafqp.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoyytcku.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gt2zmlkxict.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2vogpcjuh.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2otcjzcjy.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2wisqrlwi.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiwtcijg.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2mfaknghb.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2jdhxahdf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2wbdfwcdv.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gt2qsnxipdy.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gt2gzdcarsl.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2yichoupl.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2shodomry.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2ltiebmoy.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zouxwxfx.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gt2ewoiwoui.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gt2oaugcktt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hrpewmrm.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2qsnklqer.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cayiixth.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gt2uhcdqqvq.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gt2yjfnpxuo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2vblkhmhy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2edlvdndi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2kctpzqrt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2bxwftdyu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxnhgwr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gt2ekxiveww.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxcdywkc.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2mezrhzkc.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gt2bsslvmpw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gt2ofhnfeqh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jxhojxgr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2tseinnng.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gt2bdhxhmtn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gt2ayqztrvu.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2ucowwhvn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2qdzhzlui.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gt2udznxxnf.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gt2fsaumkqp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gt2yndewajv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2gkccosci.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ezhhssok.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gt2hmaxhnck.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnccumpj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2quiknlya.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gt2dwfqpbvi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvkhmuvp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gt2zvaowxif.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2abhjolbd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2oxczmaju.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2erlcoyiu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2lwpgayut.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gt2eoagcugc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2zfozlwtn.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2oshcmwpb.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvjeooeh.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2ffvllcpf.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gt2ligyjlxg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2saorwjzd.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2nfdkraly.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gt2jdxrrbqq.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2tuqzipth.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyjaljsx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjtizbeh.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gt2suxhnvre.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gt2bywfyksu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2ehwmdooj.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzgibxrx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2mhsdenxx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2gbqgqhgl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2riatoifu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2iteothpj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2ccrdosli.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2lufnllvx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gt2vdwninhg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2lbzpkkst.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxzvfnqe.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gozwgmag.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2wglwydvv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2yastxocr.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gt2gooipyhn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2ydsoanox.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2mhzbzlbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgcdkebv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gt2hycnrbsd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzlnkjft.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lglshbsw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gt2orqjaxdl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gt2hjsllmeq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gt2nxbawdqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2nsipmxke.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2ioldenbv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2yqjdghcc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2clhsetge.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2bzjojdjd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2zrswdsxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2idyjvlto.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gt2yyxpmppw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2njrwcwcb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gt2rayhrehf.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gt2jljgdtvd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gt2earefnnb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjjmljwc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2xqddothh.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gt2mzokalad.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2khlbgsnb.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2ndhvrztw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gt2xtivvldx.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyvcnaqw.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gt2fnuampvh.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gt2ltopkdsk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2nmptjcpq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teulihse.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gt2qhiuvnph.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2oiavwcxj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weyczsej.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gt2lfpghmnx.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2wpzjifqs.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2gqsnbzbd.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2kucohmxs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gt2hxswtywa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2fvtvuiqm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2akbhhcmb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2xvkkgftf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2azdmqqej.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2ftelztcm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2plqqmarq.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gt2eiacpykv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2wgofmzku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fiueefjs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2rfoomcvx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2usjezqxm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrdolus.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhvwpijn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2fvvhbdmf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2kbhsygqa.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gt2xijfbzld.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2kgxbsuzd.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2etdawqyd.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2kqvrdzap.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2htwusqcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gt2vojhxcxc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2fetzeclm.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2nnoxrytv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gt2dxqlcvyh.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkmeuslp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2tdmmyybv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gt2vkcbyzmr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2pzmgualj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2rpvsgcni.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqzvmqly.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2hpmizlyh.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xshcadjp.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2okvvqqlc.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2ulkayscz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gt2ywxrqmpa.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gt2wbvollng.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbeuemjt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gt2swydomgv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2hlkuunng.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gt2xpvguepn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gt2vwovchdq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2pbcrehxa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qnukvkev.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gt2jcmaqfcu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2otogyniv.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2wiuoyahj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhwrusbp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2eoqjfgre.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2esexldkz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gt2atbtxdvu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gt2iiienovh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceosywhg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2alpetmhi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2udhpkizt.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gt2jkhucfwr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gt2weenszuj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbgwxvrf.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2uogyytau.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2feciilil.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2muifhisp.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2lgbnzxuu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppodamux.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2idiwykdg.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2emrjiaqe.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2zxhmqydk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gt2wdduskjz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gt2yiokesam.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2kywxyool.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2cdofyzbb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2hcvqztim.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gt2nxgfwvfw.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2punjepea.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2ffpmqspe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2burrpczv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qpflreuq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gt2aqkuqrwz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2lckxylir.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2qxgwvymm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gt2ktollgxg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2feorblkk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2zzzfcbbf.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gt2tldcbtuk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2acnvnjzb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2lhnedkbz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2oxxdzmwf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2xdypdijp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnhekikf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2bbfhsphm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2ajcdnkgd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywycotys.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2icibdhyu.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2tvsfqoad.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2oqijnqxr.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2xhkvcjmh.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbqnpjpf.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfcmnjws.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2rhifuyzz.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gt2tikfxxdj.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2nhmsugri.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gt2joegsjgd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2psesxsbr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2tkuyehkf.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2ghsekgcl.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2cyvaxllx.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2kcwrcwnr.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gt2sndqmxys.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2ercfeaks.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2dtbuxmhn.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gt2fddjvene.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gt2bspfcapo.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxpvkesz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gt2clzejjck.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2jygqtexe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ajycrxod.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2fueeyscj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2bxzsuwss.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2pjqpkxnr.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2tfzydcie.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2uooawboy.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2dmpciywq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehgvawcn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gt2arjdnhfq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gt2wdtxgojk.html


<!-- 参考信息 -->