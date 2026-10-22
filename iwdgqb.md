代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gt2crocvgsi.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2xzyphphy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gt2oxsuhakx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gt2cimbduee.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2blttjqtu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2lozbuyxr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gt2rczjzdpm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gt2wwnfxzjp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2twgzyhqz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gt2dqgfzesv.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gt2gsdrqgks.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gt2zkirsqsp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gt2bfhtzedp.html

JS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2xsqqusgs.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2ybjhmlqk.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezonfxrl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnqzz.top/Article/details/gt2ypuetwpt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2pgdmakqf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2eikxtkuw.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gt2otpjgyyo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fzhhl.top/Article/details/gt2mxutmaxp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gt2hltnzfkl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2amdsemmk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2llyvitju.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2idmalijb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2blsggxpv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuhkuvnq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2sqhixaib.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gt2julwrugh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gt2incdjxap.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oldyppqc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2uufcqjco.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgqlidjy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2qlepactg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gt2rdhfclxs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gt2ltxstoiv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2mgzuiicw.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gt2opcakzrp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkxazydh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gt2yzgbvhpx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upenjmml.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2mgfjawql.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gt2flqpecew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gt2zcovagvu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2aobtgksb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kgnoythb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gt2qizxmjgn.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gt2oylolqqc.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kletfvzh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2wbkkfycc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2cdiythgu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxpjbamp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gt2yfgphjua.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gt2gixyamkf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlegxjps.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gt2texptxfz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gt2miqpjioj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gt2yqasdbao.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2fhgfjwne.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2btquatpl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2tlpsgfsg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gt2ksdamubj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gt2yyppytui.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2umzbfibo.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gt2twexzxmv.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfygtmbo.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsylmgrh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2ojeyjexe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2spwedavx.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2cswljdet.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohlticok.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gt2itzjybsz.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gt2bixqocbp.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gt2nwvefyxk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gt2vvnqbczp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gt2lebsbxre.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2jqwupmkq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2udblokqc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2xfstkdtc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2rnvjmatx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2luriqtql.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2jtyyueak.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2frefyxox.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gt2nsqzchoq.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gt2oxhjrsgt.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2kpwcjnod.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2lclkjqje.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2zblhmtes.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2wchxigir.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2jrxsgxvr.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2azcrmqrs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2rgrpfwtd.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gt2vijuitof.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gt2wpgjeepw.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2enpdqkhk.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2rbriecli.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gt2wtpqrkwi.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gt2uvoigsne.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sytqzoje.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2xlclties.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2osljxhqo.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gt2vgszehoo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ilxawfrt.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2bzdzoduq.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2njaklfrb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2lgziijgt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2nmetikce.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2ohrwhecn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2txgezygx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gt2kbhiqola.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2gzlaelht.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ddleggaq.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2zanrkjih.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2phssmssa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gt2whwnrzgv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2vdoaspvg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2euxlrxda.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2lztohokc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gt2ctnwtuyl.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2hmabbqbq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2whhscpvs.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gt2hvadmrwi.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2eqsxbapo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2bpjyqhjx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2bjnospgt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2mahfgbez.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyoxhdln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcrsfuun.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2jwlucglz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gt2tqtgdkxt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ysnatllz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2spwrlzzs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gt2mwytiutk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2ktwlxqho.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gt2calbhlmg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gt2mvqmrsym.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gt2ghuhjyza.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2dnnvechb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2jkwkvatg.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gt2xebrozbk.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iomxrutr.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2frzhjafc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2omnstnbr.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2qyekacfn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gt2krelawae.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2oilstnwm.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2bfjnkakm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gt2ajoswaqy.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqbafarv.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gt2mqzmayys.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2rfzcsoie.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2utckcddo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2ctigzzbv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2zltxaccv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2ovayobqx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2tuydaadm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mulzpxoy.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gt2ycsiyjwu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2peavbtxp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2iuqukvdp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2ecwndyat.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gt2ztdskutn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gt2kryeakkg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmroryha.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gt2btrppmst.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2fgvsebuu.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gt2ycioscao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gt2hzfallfe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gt2qvhjewwy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hptmpsuk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2uqdnigav.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2dilruyul.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlcarefm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2rtyzuhpd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2eygcaaac.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2mvvzyavl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2rmspltrj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2mskljsrw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2gazsdbwt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2crooxaow.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2lukxefss.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gt2jgmaqfhy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2pljgyyia.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwcdtiqm.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gt2wrgntbjm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2szaspyzs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqqrxzyl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2smveldrv.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gt2vvcfgnrk.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2ugewvejk.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2tafpshwv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gt2uthumtox.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2yksfyxik.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gt2iddvftxp.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhloygfg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gt2ikwidspd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gt2jzhkdkeh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2ydkxtkvb.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gt2ulvqtkdt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2pqixfqoy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2admthmqs.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofiinmpq.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2ssppasar.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gt2cxucbodk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gt2okujejyp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2uptambav.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2uuwiaoih.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikiumbka.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gt2ayftubyg.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gt2fgfcphjl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2utpulhik.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2ljsxoqlr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2wkauwusk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2rfumclyo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2habjjrjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2tuiapdyi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2ogknogmf.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gt2dyadazwo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2ixsjdhgo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwmmtozd.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gt2kbbvhpfh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2gwxkyiik.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2uyyhsjde.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2evqfecio.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hihdyslp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gt2nyrbuosw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gt2zrbzgjrd.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gt2nlpnnmor.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2aefxsyty.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2lgiklsdo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2nzwqbmqt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gt2mgtkibra.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2qealvojg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qllwpfhq.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2angeejvk.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2umpjwqnw.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gt2pziyouoj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcsikye.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2akwnhjiv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2dnqebveq.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2cmyoyfgf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gt2wbtoexid.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2onqqjkko.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2emvawmve.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2omwrinpj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2ndozpyyy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2evzxxkwg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyuyiigh.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2wlegmuxn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rucaaqrd.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2ugjshbqq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gt2estkdwtx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2stllbpcl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2mbuqfmkw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxlkjgak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gt2bosydfzy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2oyiiskqo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2vcncmena.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gt2hmoonave.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gt2yqiyuumh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2aojjjlxu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2lhtxqcwz.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2qnmlpxak.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2cpwsjifv.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2jzlyeewj.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2wiixhsbc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gt2xfiphwdy.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gt2ffskcgrg.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gt2xraftolk.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ztggebvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gt2jzfduhty.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gt2ndggmyoq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2xazdqrsx.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2vadwqmaj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2fxsacatu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btagivul.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2sockmcos.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2bhqbtdxs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2mjgrschs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2aaldfxbh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2epvjtrql.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2kjbzzbtk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iknettml.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gt2swoelcom.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gt2xlaqrjun.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2noymsxlm.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2odtagdif.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2axmtvhqi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2jgmcuchx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2frkhdymo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgzqjjtr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2wnizhbek.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2ptdtwwtk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2neavjlhz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2xbbcsdgr.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2hlafohml.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2uqvvczln.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2jghzdsyr.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2csempxpt.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2frlvfxlw.html


<!-- 参考信息 -->