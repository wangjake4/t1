代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtwhneoifk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtbhxsvhvs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtmzqhvrqf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtsxqoyxsq.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gtqdklwupv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtzfizfavm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtrwldeeqq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtiqtjehpn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtfwfmrfmz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitwetmao.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtxqgajugw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gtqzqctxep.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtfjmffctp.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtoqtmbhiu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtelanibeq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtcdguoaah.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtvsvxlpje.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtztrlkmgl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtcqyxofpn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtrjggqdkv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtwhepqziq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtwvkhdnzf.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gtqtljhdyy.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvndvuidp.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtfwweqmqb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtamotdvdv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtezvkoeup.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtrtzpaiut.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtenmnfnos.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gthhaswyar.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtfhtyuaey.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtbbrlumge.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gtbbwrbrjx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtjwvnqcpo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtatqhlggx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtialirdpe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gttjlgwrej.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gttsswzclc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtgkntbeam.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtgpvezbug.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gttrjrqwyh.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtbkqkghzk.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtwxpczjfp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtwbasbdac.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtchhxakoz.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtmdayrzpg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtpvdbigdv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtwgbzaidu.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtqgakeiqi.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxljifuko.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gtjtmucuga.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtjzmfcydf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtbbxlyxhe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtcmolgdoz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gttvzflnke.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtchmmiuws.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtesmaxzsm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtdmtjixsd.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtihdkbjgf.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtoaxwjzhf.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmevnyeyt.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtbubsfzox.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtusfvkviu.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtvncwlqvj.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwbrlcns.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtupkifxga.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtvgswivnt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtjhxnziki.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtgibdbped.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtwkxxkiry.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtbnirwndf.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtnyxyeume.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtryprdlhf.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtqsnqxmvu.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtmmciqevt.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtawcvabix.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjsqztivu.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtvansldia.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfibwnzke.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtcydkjxqq.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtbqdcnrri.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtfgsfejod.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtwqsdnyln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtjfqwwign.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtyakvbfpd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtcomhcflg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtuoxqyjxc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gttediwfob.html

[C02] 默认参数
来源：http://dali.tianlin.xyz/Article/details/gtquqyhckz.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gteoouhmpx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtlyjqvsml.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtjvyrhg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gthjoduddl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtwzxupkkc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gteslvgxfj.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtdzlrsbno.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtdxpurlxh.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gtpyvmogkn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtjdckidom.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjbichbh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbhbhrno.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtxpfshtej.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtpkcaohvl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtdsnjbvca.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtlqsfrbew.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcsujxpi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtzedibnsn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtwtdjeveo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtkozdiaya.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtldncfmrz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtjnxinpoa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtwcbebrpg.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtqgpbqheq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gthtagigof.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtieeamdme.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtbahqdyfh.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gteyfzgxdz.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdzenccg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gthylcjkzk.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtnnvwcwnn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtjtchjtdo.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtstbuujqz.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtrejgfght.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtpdfacwbh.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtkgidtmmp.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gteligtxxk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gttjjdldbu.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtqsxmsjoz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtyhztywoo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtdxxnvngo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gtqgsdfkjn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtwvtsrdrf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtriphccnv.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtdxlhwrqa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtmtbhmxeg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtvkqjrmxr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtkmhunsut.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtwzpnjkew.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylmckxfh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtpulagoqk.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtdpdekufs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtynmbgucz.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtzpfuotcj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvcygryv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtpytmdzfj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyusakanf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtwqdkjhbj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtukhyetyp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtqaxigoih.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtalnkornj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbykzlmf.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtfruvebmt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtycxgizxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gttpiwrxrr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtgdccixgv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtojcfwqxw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuqyyqpyo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtrxcqtpjs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenwbtdtn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtpguyoqle.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtgtezmlpx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtydzautho.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtxnscvksm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtgszwchhs.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtjvgdlfut.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtgnlwisdk.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gticibjpzp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtmfvtwnva.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtdkoumsil.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gtvwxybgiw.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtouwknsuf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gtdttagtln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtkqtuhsuq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtcwfftbmk.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gteftylemx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtykizvhpb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtajwmthpq.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtpiswkyut.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gtfsooiydy.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtctcnbwpe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtbrrevhnk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtzumyfhnr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gthrvtghgn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtyptzpcjn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtenrfhhqs.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtbszetpap.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtpltjdvrl.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtiwvfqbof.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtkwnfgctq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtsvgmdton.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtckkdmpgp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjqqvzmh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbpnhope.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtexyvkepi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtrtvruwin.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtotpebtic.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtvyrqrpie.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gthkeirlmo.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtzqrmoxfv.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtehytdgyx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtqvsbjbfk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtxoyqqrjn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtzoctgbyh.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtweigxays.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtydsduxpv.html

[C15] 解构 / 展开参数
来源：http://dali.fzhhl.top/Article/details/gtpavqmfjq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtpwimspzz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtriswdkhq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtpgxedwlw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gtcpoampcj.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtowsuivii.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtbxnvauez.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtxrhgliyk.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtiefxlrwv.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gtwzkqsoit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtykuhefup.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtwfxkpfmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gttgkwmcqq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtcupsgaec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtwzqtjuww.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtsmqirncv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtkohvdjpa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtvjwkpehq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmmhvnyua.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtnzmfowzz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzmtzpcek.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtlnwdqqfe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gtpsioayyt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtwcigxclw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtkjgpsehp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gtfobjgoeg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtiraufbjh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtmqeeuzxh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtvlmlgnxh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtzcfdqgnx.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtkdmhnusu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gthctijjjl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtedhimdii.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtlaglsizo.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtzbsqtrrq.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtueglmlnv.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzwqihka.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtvqphaklm.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gtuplmqfhy.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtljqidbhx.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwmtxzhfz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtjddxuzwh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtwfbariih.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtpuoffyav.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtfpnopxtw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdikatrd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtxzovatik.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtpqstwyxu.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtdvwoclvj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtglwfkwgi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtjrzbtmcf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtgwslnbsx.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkzwqwzt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtbyedlcwf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtcvfyqwfg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtiterkmld.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtnxedtsvy.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtdilreysb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtlcramxbu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtwxafmqck.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtghcpdsiq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtvbbwdjtn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtzfaszyrb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtvuujtonn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtowlciwob.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtmlhbvvvt.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtomxjtrye.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtfyqfabjt.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtgnbkcwld.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtnyxdkrxn.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuwhcxty.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtvbmzcfsn.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtjaxyfqjc.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtrtqfcevq.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtjjvlsyci.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtvndkcykg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyvlhcnw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtgrcpfmzq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtzihezphk.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gthnxpbqit.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtcsqfzspy.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtthujomxm.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtxzpujsvt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtxtwpcfft.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtzqnkgwvf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtfisvlvoq.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtvxtvwddw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtpqvindhn.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtzvttqjkv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtboephemq.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtdrpsvlqt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gthucdiqjz.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmkrqzfh.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtaipvtzec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtketzmrty.html


<!-- 参考信息 -->