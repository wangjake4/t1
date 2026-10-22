代发 wailian999

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gt2pyuwshym.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gt2ulvqzdao.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2jpleitjj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2jhrkcaug.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2jiwjygtk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmwfmcjx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gt2ftuuawkk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gt2xowakarc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2ummkhugr.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2lttgcumk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gt2abqfsduc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ormvyobr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2yqhwbuwd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2fynexzes.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gt2ixisstyp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gt2uvfnmslh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2rsnmxxuw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxccwyuf.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzatvkys.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gt2pjophild.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ecxmnsbs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2abvugnah.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2qraopape.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2iqmirxlv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmxiooxb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2zsvfrykg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2kkksxffg.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gt2hobwrkxr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gt2xdcsohlx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpfetmpk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2ykjgiukm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2brmwcuyb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2ishwqqje.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gt2ualmqcjx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vscmqueo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2hliowesf.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2iuvhnpwa.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2swodkwzd.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gt2tcukjxsn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2nhvfziqi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gt2txhhbxha.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gt2lqwcdmmy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gt2uchtrnii.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gt2ckpvehwm.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gt2orzwpkxm.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2bogonlab.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2ogxfccly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gt2sunljrxx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2jnykrycg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2lklngkpk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2wjorantc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2tgyhewpt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ptwscrvi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2epybgrxe.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2cynnehcz.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gt2ooggvjcw.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2sbvkhdgm.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2zqemjdle.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2mngitckm.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2rfwlelni.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2czyeoipg.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wddjuloc.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2hbykjnsg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gt2tmhmmtqz.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlxpscrc.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2bupjeytr.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gt2aefmijrx.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gt2axzyvnkq.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2gikauenn.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gt2hnzactfd.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gt2ulsfqyyq.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2botkvlrh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2twxuvqff.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gt2xgyjfqja.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2aoiikdax.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2icbwfzxy.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gt2dqdvmiok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2vvyvruld.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2dnyldxzk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2gdygprop.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbzfasjm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gt2tpmkfuef.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gt2gnogmili.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2xitqntgk.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2lsoygmaj.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gt2zcthvrnk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gt2oisniqiz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2mmraykbi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2dqahapes.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghofkjsq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2gwxjjzeq.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2gfuykuql.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gt2wdvvvpbc.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qonxctmg.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftnhnbkl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqusucjy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxsmsxqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2lqjuwlxu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tqgwdzgg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqqpggmm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnztsxlz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gt2ngxbosde.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2xkeabffj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gt2akrshsxk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2aedrazpe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2acmrbrsn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2mmqqirie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gt2polsezng.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2vbncqcjd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2gfcjzvtg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqaajurf.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2ymgfmmdc.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2pggcklxl.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2affupqec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2tlzvylon.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2tdyuqxtr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gt2liahkswd.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2vypymnqa.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoqwaqnu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktbqfrog.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2aoywnzmh.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2szgujhov.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gt2brwpfpmf.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2ozqjosvz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2lybsngjk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2iddjferw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gt2nuwbggze.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2jlnzqmmg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2tqpfnhjk.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gt2nurdvuzn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gt2mxjfrdvq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2bdscmgmj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2davpcwfe.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gt2lkizgjbc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2adgipqup.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gt2vupnqppg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2exzgruvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gt2nowxrgap.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2tktebpbp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gt2ooxsbrpd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2nzqjlnev.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2zdpsnnns.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2esavpnvv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2fhfobeih.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gt2xiszhtbq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gt2dicsfopk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2izfxyhbm.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gt2rupcpfwc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2dnhhcqfn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gunylvpg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2eumymfge.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2yoksflva.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2zaohhrgj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gt2istclmjl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2vylwgkda.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gt2ptjnevjx.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gt2quhqffub.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2prihsdlz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gt2mmzlaokj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2zynawsrl.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2gpawxsac.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2zybzembk.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gt2zkhaonhr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gt2baoobxjs.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2qjjmwpni.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gt2usgucbco.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfwxztoh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gt2pytiyhyv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2plehtkfr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2iuinxjuk.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2qiuucrkw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2asysapmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuoppgyb.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gt2nadghzve.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gt2ezkdkcsd.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2lcmidxai.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2drejfvkz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2urjgudig.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2bpdeuqqo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2dvspvkkh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2drwrxtkh.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsqudwnd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2rhbwuxki.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gt2noyfsilt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2agpuejtw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwgthtdw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gt2axfblrjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2jnjhpazt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2mwxamnzu.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2iuvphqgr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2losawgiy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gt2ibziahao.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gt2erqbvmcy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gt2anekfdzz.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2mfztvsur.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2icbmzjvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qbasbjfn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2doxfmwdb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gt2vtsrmuap.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2kpzvbpmy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkfzuyhq.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2ujwijlae.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2azjicsaf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gt2mlhpxumh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2betocuml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2qihaslzp.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2tecdidfl.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2cjyoppva.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjjazcyn.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2duhlqkrm.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gt2qwjzjonf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gt2mikrtgux.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2ghskyudf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2zghxyzzk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gt2detkizey.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahayowor.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gt2fpdpwnto.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2cmcrjkuw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gt2pnjodjup.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rygwulrv.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gt2yfkatwws.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ythlkyzr.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2fpbjaxak.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gt2rhrlyuzt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2ogntilyj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2qbsxfdim.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2hlfsskxx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2pfabbcrg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2icskdonv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gt2ubqwclko.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2offwqene.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gt2ukwdgndq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2xlpgwrgt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2jlxxdxkc.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2lkxsghfo.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2jsblmikp.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2jhrrbsxr.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2uibqmvfq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqerpyfo.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrslyabk.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gt2ipkkksfu.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2adzdjihh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2mfmosogf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gt2jjhxtpvx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2vfosjkvs.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2jlzhvenb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2ormgnstt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gt2sevtdxzs.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2zvjgoqwe.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gt2vszprdee.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2yffbrlbb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2jdebuxqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gt2ouoojimf.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2vrlcmnzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2vaiyqzuw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gt2ypieasdf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2jyvdpqtc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gt2iahgjsex.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gt2icvjudtr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2csvdvkjx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2oasflqtr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2kbqdfvgl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2iklxbbem.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2ztmpwtwt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2ahqycwir.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2wiotocyb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdeezabt.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2mffgtibz.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2zklfxgjk.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2dappsbni.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2ollenesq.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2vyvgvvlz.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2vvscgcjs.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2evotfnoz.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gt2oveaxkam.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gt2yvbhcmnb.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gt2ultvghuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gt2obaoltiq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2jpvvynps.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2ynougfuz.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2buikigft.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2hohvpxnj.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gt2vtakerez.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2bsuuwbsx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2qjhutwkl.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gt2ezrrrrsk.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ydetydhk.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gt2agdytawp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2hcazsnka.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2zikoeyee.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2ofjupclo.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2evabusal.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gt2ktvjhtad.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2tmfshvtu.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gt2blhviyrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2hpvkzjem.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2faozufmm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gt2gtzlmczn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gt2lwkpfmhm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gt2jbvlzpgp.html


<!-- 参考信息 -->