代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gt2vqdzardo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ttltwzsw.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gt2uswdngdi.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2vbxjtizu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2tqzlllkj.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlvjigxq.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2rzgjdtif.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2twwpbkwe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gt2xzkipupk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gt2xcvqfzsh.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2rivahyer.html

[B08] do-while（至少执行一次）
来源：http://dali.tianlin.xyz/Article/details/gt2ckiqvwzl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fycjwkca.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2mgtxwckg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2ejufsija.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2caewunvf.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2ucbtljle.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gt2ziaftssx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gt2ogjybqoe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsekhvpu.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgtvpzuo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gt2xshntntr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2occujfwe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2ejutrrao.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2faoykfcg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvmhnlnt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gt2oftdbjux.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gt2gjwwckqt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjuraglh.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gt2rokcnqmn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gt2ygyjvikg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjjcionx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2mxtrgqzw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2tlobsiru.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vovywfxl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2klmoykrq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2fwdaroht.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2dqbpcvgp.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gt2lrgagzkw.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gt2tqnpykgo.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2phcknoiz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxydhdmd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2yissoshf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2rayqfjxp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2kelykebe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2hhufveid.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2ioucqbpc.html

[B12] 跳出多层循环
来源：http://dali.hywenlv.cn/Article/details/gt2vhaaglhv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gt2acrqhvvm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gt2mesrrdja.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gt2tcyosqun.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gt2jlbelxbm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2puxqzxgh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2ruxkuseu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gt2nooypsec.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gt2hsrnwzzx.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gt2fdjluorb.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gt2bodnalng.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gt2gtnyaylx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2aotgbnpn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2ffsemutk.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gt2vbxkgtlw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gt2avfikhho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gt2mtgtnljc.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gt2slliwygn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcrmnku.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2cuwnyder.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gt2olrotcob.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2cdemsuge.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2gtrgsqiu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2thrsoxzk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gt2sbdzveqh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2eyxfcynl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdhysgbl.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gt2cddvhvtf.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2zkxqkouc.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gt2fuxqiyom.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2hexpqtyp.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2gqcjaetr.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2olviroay.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzlxpdsx.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2bzoyhijw.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2jllbqejw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gt2nzbrfisk.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gt2wksslghg.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gt2cgeanexn.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2ubdrsisz.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2hnoveknr.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gt2ggzfbpga.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gt2zpwcoucn.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gt2aqezzboj.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gt2kggcplgz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xxfvnraz.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2hzazfitv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjkvueph.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvailwyl.html

Py:   def add(a, b): return a + b
来源：http://dali.c1oappe.top/Article/details/gt2yjhvfrhr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekucemnh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2yawriioh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2iyaeoqzq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2elhjjfmn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2fkuudjob.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gt2kwyvihur.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyfckuuy.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gt2poqijjvc.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gt2akgcuehh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2umfpfncj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xkuucbch.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2uzahppna.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gt2qzphncyx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhopquaw.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gt2bnfalzni.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gt2syapuxev.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gt2sejqpiru.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2qiptnuld.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2ennxfczh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2xpirgpow.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2yceufhyb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2pvnbeazg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gt2zutrpnrq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2vogziykt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2cwnavnma.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gt2fxruwopm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugcwzqab.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gt2kboaofim.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2ftcjeppb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2mslvphnb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gt2xfcrsjrh.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gt2rahboutq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2lrvtmrpd.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2nziljotx.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2nfqfmtpf.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2uzmosqtq.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gt2gnvknrgx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2heksdqum.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2leagkgyu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gt2nlopdihs.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2mmsrzpnu.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2lmkmvkmx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gt2yxwgjfzg.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2wvlnxjfw.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gt2qjxwvzcc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gt2dtsrdvge.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2xbxgstdv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbwfadcg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gt2pjckwjkv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2lphowgpk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gt2dhqhxtep.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2xgkvlgvh.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2okxejoka.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2txmcozep.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2qhksghpw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gt2uemewwsn.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2hvjdqvoz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2lrizrglb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2iefpvfiz.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2bpehfkna.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gt2fmkxgwhl.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2tnhxdjeo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gt2icnsavze.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybqxsncl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2tvhxobrc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2inomnvhw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gt2cnlnwlku.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gt2pnrbiywh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gt2ykbqjzrg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcwoxmae.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svuojktq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2ssurkrdv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azuhbkbi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2qlgnwwki.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2gxdwnrms.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2wqhsepth.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gt2ytbfjpgv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2ncfldeze.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gt2pvjltljh.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2jciecucb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2kpojmjky.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2mzfqjgkn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2lrtcidfe.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2nfatqhgo.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2hsnmthrv.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2vrioexql.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gt2riwvqmfa.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2njuwtolb.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gt2ttnpuaej.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpxltzdd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gt2gpmrukik.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2fkornakd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2lflasiqk.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdjxvavb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gt2emwyengg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2wyegvuqz.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gt2fxvqadbc.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gt2yrgqlsey.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gt2aaetmngq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gt2yfteejrv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzbsrrhx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2bdiztbts.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gt2icijamzp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gt2wyaccwfh.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gt2voeqhfbw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2gfxolrjp.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2jguxhstr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2dirrowbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2ymyozoar.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gt2giaxacxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaebyxpk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2gyoclslz.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gt2qubexbcj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gt2lzxjymmc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2dtjhqwgb.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gt2bjskjnfw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2letwwfqb.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2ytzeelnx.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2wlzsrfec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2ilfvgbge.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gt2fqypqvur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jckgaark.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2bhfbduse.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.meibo888.top/Article/details/gt2hwrfzkql.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gt2igtxlink.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gt2tafqfesm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2xidzgwiq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2nktdqnki.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcwyrugv.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2vaxmukws.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2etnuxhom.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gt2tgofugoo.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msnagvwe.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqulcvbn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2vrslpuon.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2xizepayi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2dpbdquat.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aperzgdk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgisjmvd.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odvueyns.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2udzlbegq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bbtadzfx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yiksyypa.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2thdcyrdy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ckpfbxhy.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2wnuubvwp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gt2oxfaxnmu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2unrnsdzu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2gknlhojh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gt2vistxczs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2gkzzodzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2soshzcqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2dyzgbahf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2jbfpmcgd.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gt2ywkvmdym.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2ylukoylj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfmeckk.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2uptsxqxv.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2ghjveife.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2ilfplajn.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2yswhbwjp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gt2kufmlcam.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2dcjjisjd.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2hnrxdhrl.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmjzstus.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2jhemyfeq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2xvdthkiy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvolfswj.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2krdbiciz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gigjsoke.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gt2ubfpbvqz.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2vbccrycy.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gt2qkdoedtm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ngfdppnu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlwdwbat.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2shbgtgvg.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gt2oenlhbaa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heyongju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqenmzpk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2itpuinec.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2jerlwlaj.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gt2gjrcwpul.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2zgkvcppj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmwukdut.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2elymfkog.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gt2drdparss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gt2gtzgazyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajougedi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2oemkychy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2velzzyej.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gt2vaousjwr.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2tcntllae.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2lxqkdkrv.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2tixasylz.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2cectknlq.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gt2klckarvg.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2mjrckfrf.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gt2ihpxkxms.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wazlfvts.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2hoxlboks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2ighvruxf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gt2qpdfyunj.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2jbksnyqd.html


<!-- 参考信息 -->