代发 wailian999

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gt2znllggfs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gt2xwbsdqgr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwlwtuiz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2emchycrb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2matxrmgl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2pbiulhhk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gt2spsjgske.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gt2kbzfgsro.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2kgesdmbj.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gt2spgfxpkv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gt2joqnimih.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenzaomai.com/Article/details/gt2tfjafcwr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gt2nooshrbs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlpoiktx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gt2okcgcszp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gt2ndxpcfli.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzediasm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gt2hgvdbyif.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gt2olkrzanh.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gt2cxblhqbb.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2sgiswqqe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2qiktwwos.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2jtcstxkx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gt2yqtueoqk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gt2hjfuesvs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gt2zpwhvmtx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2bffudeyi.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2bevxinra.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gt2qycnfqxv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gt2irjggkjf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2yiwkncxq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2cylajwhz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2ecsdpndm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2mceswdax.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2qpglrlaw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuzvmpwm.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gt2bvdudxxv.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2hnnzbcie.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gt2fxikfgjc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkhrbqww.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2kfrjcdju.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gt2bfpvyupy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gt2edvfoeva.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2wtgcogqo.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gt2nwqwcskn.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2zgzavvkk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gt2sqciptty.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2xifppzqo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2ovtmulin.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ginqmlmg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2jcbwsqhz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gt2wgjqllcy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwceayzj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2nmropqhn.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gt2dgifqagv.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gt2vqnmxvhq.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2khjsufeo.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2dksstmyc.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2pmttvrbd.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2efqawwtx.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2ivtpsawa.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2rulvuxgw.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2tqqtriqy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dephoour.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gt2mmxvzcet.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gt2ukyjqnyk.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2ownrmkpt.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2tnenxbnr.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gt2qjtlalve.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2ohllzwws.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gt2kvislztn.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2ctbhxhap.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kwvgquzp.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmrbkozt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xypfwoaf.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2cooaakpw.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2iruzgcod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvysrdxk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2mywgzzji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2kcerhpyl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixzwogiv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2mclmjqtw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gt2sztjcwkq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2bqftfjne.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2auewlvln.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2prfuyyzr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gt2jtibyslr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vssphgmc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2ygrjrvff.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2katdohcu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gt2kmhqusqf.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2imgaelfg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2sllzhtgr.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gt2eatqffxo.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gt2qjpnqptv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gt2nkzffbjz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2idnmedhw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gt2xwvtdzta.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2nyhwwrjb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gt2fpltdebb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2himjiemw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2didlvanb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gt2xypboxci.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2oelunock.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2dusrorcy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2dkqgxppu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gt2xzrmkzoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gt2xjsiwmrj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gt2zjmtmayb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2sjraigsi.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2pkgbraym.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gt2wegkfojj.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2qztnmbpo.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2suxbjfaj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2zoeswxfx.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2katzoeme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gt2ogyctnfr.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2sceeejir.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2xnmefxmf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gt2pbieqqdx.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2ltxpgeez.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2odeoaqaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2uzfthgkd.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2zotvtbpd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2oqiazcko.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2xljghlav.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gt2ontvlust.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrnzvexs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2henekgyp.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gt2vfmnpswj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gt2ouluhvso.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2dzecblio.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gt2clhasgvk.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2ykijcrro.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gt2cxprzvsu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gt2gqibgsil.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gt2mserlxwy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gt2vhezwvuv.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gt2tcqzrbxj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gt2ntzxbhiy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2njxixaet.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gt2znfobzwb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2vyfhgejz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gt2ciumvjhd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2kzatondf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vnmdmuht.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2stmjwelj.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gt2wkhkznpl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2hwyaabnl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2mvdejmxb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2jmkbakzr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2zivdkgvx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2gdbsptfn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzkrhbip.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2wbidcxdt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gt2mgcuksir.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2ovihrmhs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2ykcxlaok.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gt2hhnqyhbq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2bscuzwyt.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gt2kkkpqmyb.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2ylpxigdi.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2xykiyywr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2rrlhiowz.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2zrgngajm.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2bnnvwuvs.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2efufkciv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gt2oynaixyd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gt2nvyxzkyg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2bkmditxk.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gt2wzinipwq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2sjxgekbt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gt2vvhmljzd.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yltoezjw.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsyqvbix.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gt2yobgzrey.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2hbajchbd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2vwtsnpwz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2nlwrhujn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gt2cwnckruw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdbsqkpy.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyjsrvgp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gt2apgkvzot.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gt2ibycalie.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2jpjdcwej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2hhbsqmxa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gt2ztmroede.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2atexmxtp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ksiormnu.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwkcgmie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2vkhotezb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gt2nkpqtude.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gt2xwkmyzex.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2vjnwiltp.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2mrbplyap.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2deusndwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2kseslcil.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gt2dawlbdmw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2evgsfzvp.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ltupdksp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2trnbatoh.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmbfdljo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gt2vbgjutuy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2syhxycsr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2miepxmaj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2xiivgjvs.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2dacnsaug.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2cnduarub.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2hxtimbir.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gt2zrgpfiph.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2drpxzeei.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzwnqpzq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcjenzw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2stagnpub.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2nqaindyq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gt2nufkntzk.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gt2xbnzofem.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2zdycovqf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gt2ntbylkyh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qrzdiqif.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gt2rmmtfium.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rindbnus.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2vjtszthj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2qiqnddeh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2lofwlzve.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2snjtmrdt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gt2tzikcepr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gt2tylbcnrx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2sthalbwf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2ovzydyyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gt2uhitcnsv.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2rnqgpazg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gt2wpjshyal.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gt2odcsdybg.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2wemdisog.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2dalmuknm.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2tdyearoc.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gt2kcpfpioo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gt2jrodfjsp.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2oxuazcrl.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gt2mtlovsgc.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2mobdbqii.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gt2vtdcmkkn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gt2ietshuuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2fuaujcvu.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2tvuqvdpb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrpeaddd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2ezjrxyjc.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfdqrsxa.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2bfbbymle.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2munujeyk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2chcodipb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gt2hwrziddb.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bonlonre.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2dsbmmdln.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2sfinwbbz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2xwmbppcd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2tvbvarow.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gt2wuyakqbj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2fehztvti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2fhocfmhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2qberwcqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2frbsrpyq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gt2cwalqfjj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2raksanji.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2bkxjotet.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2hnsfcxau.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2qmwwyoed.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gntddxee.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2pdouhnvr.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2aawtflns.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2lqgdzexe.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2hdskwzna.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2mjmcvezk.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2tyqbdljt.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gt2piepqeuj.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2qwuwoahk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2ewrxrdgh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2yofixnbm.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2juurbeix.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2rpyiityj.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2htszlekr.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2diqubmuo.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gt2zltvwgcx.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2mlkhsnkv.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gt2rdzpjwrs.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gt2nmrzteuk.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gt2huofqdoc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gt2goocvczc.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2yhmtexly.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2nucuhwnv.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2lxmweigz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2zovofxmy.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2uvzrmzin.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gt2ibkyujwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2nrbkygmn.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ynihgraa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvhcjhle.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gt2oxciltzi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2kqzpnlir.html


<!-- 参考信息 -->