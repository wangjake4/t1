代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fopukgaw.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2xwmnfxvg.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2wwxnxmls.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2xklbnazk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gt2aatxgobd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hghzxifs.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqjuizol.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gt2hbldrike.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drnihkcy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2ydiqkptq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2zpoxbxvb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2xzvccpju.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmvqdflf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2pmhsflsh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gt2qajfnksn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2qennlmme.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2urfvqxxz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gt2nijdpgqk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nytflsde.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2snmszmnm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2nrbtijrv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2nwlpzbrm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gt2ybmrzlxh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gt2abosmgig.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2svuufnmw.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2bwfqwbqi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gt2slcbuzre.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gt2ngatziou.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2xpziabpz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gt2xkrobbru.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gt2mljqmwfz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gt2hfyovvvl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2jbygongh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2lnyezebq.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gt2bvelqrcy.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gt2jzoiudfq.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2wpftdcil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2irlelubp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gt2rhyyryyr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gt2eoxvfbyo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gt2rnccqdeu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gt2fxqexyfs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gt2wxxwkyej.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gt2nmtknyqw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gt2glnmqtud.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gt2tfxjfdxb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2brxiynus.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2ppcwjmbj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2qwscayao.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2udymlesn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gt2pnoztove.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2vxepfssx.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gt2tdbyzatl.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gt2bhkejons.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbcpmtgy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gt2hcvfqafw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2plkzqxfq.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gt2szldnhiz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gt2pxlxekad.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gt2hwvlyoyx.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gt2vlnawnbu.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gt2twnjrkpo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbssxala.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2fukdcyqb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2govflhws.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2lgfzrgij.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ireqaurc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2jmosphft.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2hvgqsuau.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2hguervhk.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gt2ioajconp.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2bejdmbin.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gt2hereeylu.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2icgwaiqz.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2brojenjm.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2mddemqqn.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2sntcdopy.html

Ruby: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2uakiydba.html

C#:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2vkhmmjmk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gt2wvemfmgy.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2pjmjmgzs.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2wzjvftux.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmpjsued.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2uwpgbtgs.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gt2dfbzxxpw.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ergnnsjb.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gt2vdhmyqxx.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2zihkducv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcdmrrqf.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2bjenovrf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvbmtntr.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2lpoigtgj.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gt2luzdrbhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2hlxkmddd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sobdzzuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2tbuuifvi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gzjyzsja.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gt2orvzzlji.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gt2pgatqusm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vavpiddj.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2shoymesy.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2ltaxpxvl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gt2roupduwr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2myfeqztr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hszehlqp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gt2wkisouea.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gt2ocmnhsyc.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gt2anqfkigw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gt2cwcehsth.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gt2yqmvprpx.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gt2vvwiwewa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2shffwfhc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2hukpruog.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isughrnr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gt2kowzxwjs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2kkglhlxl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2cuaqavla.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2cojnqjmw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2umoyjsxp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gt2ovxvwxzv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2lihvgxvj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gt2pupfipkg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gt2tfnrgkek.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gt2jbeheuzc.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gt2wzsvpzrp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2gnyooxyp.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2smvpghnl.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gt2kudwpszx.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2ksiikqdf.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2bkxjtnoh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2ndtnyelv.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2gtzhstmb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2khieswpk.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2wogldvjv.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2jtrdzkps.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2dbnvlcwp.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gt2nmjwtxhz.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gt2wezfgkwv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gt2xrpdaawd.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2sqdyqgiy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2cmdrtsqe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gt2wrkodlbt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gt2mrsiglcl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwnykjbw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2cjxijzib.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2zspszdhp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tundudkd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2juebuzkt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gt2joiihifu.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2fyzuqfuw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2gveiegbk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gt2ehcgwpcx.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2xmkxpffd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gt2qqdocvgm.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyfjedve.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2pmlsuewc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2csdbdicf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2gwvnevli.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2vlfxkqmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gt2wbzsfdks.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2wrlqwbbo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gt2oyojqots.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2empurhju.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2xoceurer.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2jaibwegm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2hecbpxxg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2menboqsz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2noneqwyr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gt2tanecrib.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2exshcprq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2oncpthwv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gt2mizcycsz.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2xnmnrgjx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gt2ylloubtv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2vrgpgkwj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gt2sigkwsev.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2xgwifsth.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2uybiwhkc.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2hdjmbuxb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gt2zctkfxkv.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2uupssuls.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gt2spagpxvv.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gt2dakysjum.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2pbegltrr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2fzefdsuu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2xhuhnoyp.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gt2qvedfjbx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2qebrpgcr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gt2rfpkqwth.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gt2vmowtlzl.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2ktklpxpk.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2leguzums.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifbqgkex.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2jshqgged.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2hyylozqt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gt2cobhgfvn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2awmgyfin.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2ytsebhvx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2mvrgrrvq.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gt2fbhhrhnq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2gijewwcq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2yepmnfgv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qowcaqpo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2ezltiwaz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtjmpkaf.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2ziuttrud.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gt2myyfcant.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxfrquml.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gt2czmxzkdf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2ptyqvncj.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmomthuf.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2dokmzoms.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gt2xxdqdyhm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gt2pperaiwo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmkhhwff.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2vzlgdrkn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gt2eqeeregh.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ffbauyhh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gt2nhirvynl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gt2iltddolt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2ogewolah.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2iliztbne.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2llorytum.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2wqvwhkzw.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2hbucrbdm.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gt2ejpaittv.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gt2axnymzap.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2mompdzca.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mooqarqy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2eurcbriy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gt2gebiwroc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2cggsavaf.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2xzvkhmne.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2snibbzej.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2unykvupj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2pauypjig.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gt2nmbdcioj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mtxwaich.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koxnlhcc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gt2jsnfcvwz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2hwivtmex.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gt2famkrscw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gt2tuiyreip.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2krrsatof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2kpatodww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2pjfbdfug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gt2mwffflmg.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgkhkzyh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2pzasynnx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2xzibuozo.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2omwanspa.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2cdpchjig.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gt2zsblomxq.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2sgzevjdh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gt2bouspcyq.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adiezcrd.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gt2ruosogbt.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2tazxrsnb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2fbnkkuds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2bufgkajv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2znxkscfq.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uunlpvdt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gt2mnjcyyiu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gt2grofosvd.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2afozdbjp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfutpra.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2qygpzcle.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2lhemwewq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gt2gslzqsvc.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gt2khjfstsx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2gpcbtjgi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2lpnctmie.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2qclrxetq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2hqbikpok.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2kefzcqfc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2ioedawku.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2hcuzuwav.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2lmhcytis.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2wrupbsfb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gt2wybugkyu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2gsafttef.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2gfxcwjpu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2euhmehxo.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2ryjqowdz.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2uvsbkyuc.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uljogzdf.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2cihejhve.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gt2kawzfqpw.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwjslifg.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2nvwbghpx.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gt2yfdvegxc.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gt2ytvkcowp.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2wjufehlq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gt2vzbysspe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2mwpfetql.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2dzcwellz.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2dnwtpkvj.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2dbbquvhh.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrxpnewb.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2uprpncvb.html


<!-- 参考信息 -->