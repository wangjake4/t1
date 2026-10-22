代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gt2qgddlcdi.html

[B06] 遍历字典 / 对象
来源：http://dali.yanxiufei.cn/Article/details/gt2mdjmeves.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gt2uqasulsy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ceknemsm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwystqkg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gt2peygvmen.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gt2nhshdgye.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gt2lqnxowck.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gt2tdjjooag.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gt2skponqkw.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2geaeaksu.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gt2shiffqso.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogjgjurh.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ifexwlpe.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rohlhjam.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ueuiakxc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2lbblilns.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gt2vtsaamud.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2bziilczo.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2aagoixov.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gt2lwbclbuq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2jwmcbkgp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2zvipcpun.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2czcdhajg.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2brixfehy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojjlgcdn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gt2zgfbqync.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2frwwqqor.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gt2ltleizhe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gt2nabmaetd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rlpbsvoh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2njkzkpza.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2ekosgaet.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2fcrbbrsq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gt2goohwtfy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2zqcjeiik.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2tbeeizoq.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gt2cjdebmrw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfugrxmy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gt2tmqupgms.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gt2rkmlmsre.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2wjlbfvsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzmekitg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2qpfkjkyx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwdozngk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gt2raflrwuo.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gt2pxhpfrcl.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2vlzuuvpf.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gt2uloqrkcu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2zysrgcci.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilsivthd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2yrfturku.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmsrzptf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gt2rkadlrol.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gt2tbfiwgdq.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2djdwkqkj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gt2mxtlgsou.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gt2bnuqwwkf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2iaaphovd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2vvqmmxhg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2othkbeiw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gt2soxxfztr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gt2idylzkmn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2mrnvpqny.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gt2ikrdqcxk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gt2fpvxmglx.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2zzbvznva.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2xpwdlxir.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2yoczmdgs.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gt2fxidisgs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gt2cqnmxzdp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gt2hqqslkio.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gt2smqbpwsy.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2obnigeku.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gt2vcxncjji.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gt2nrwbfiby.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gt2xqrajqyo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2udgxaaoq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gt2swcikfac.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2luauupdf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2lkfqlnhl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gt2qvdhnmhx.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gt2vnusqccp.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gt2ziaybvaz.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gt2ikbsesvu.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2imkuqyde.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuvmigrq.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2loluuacu.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2ylhttuqa.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2jozdcbja.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2tgsdmgla.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gt2blzuuesl.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2ytrsbehb.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxeuzrju.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2duziitdq.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2jhesywbx.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gt2fomugruq.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gt2frjloemp.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gt2jqbewmfr.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2vctkugod.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2pjxgsfer.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gt2flreqamb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ueqqwtbs.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2phbcsyhh.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2lsxcnpfb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2kblgbjpk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2cufqgnls.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2vosgjfbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2ajbrgzaq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2pspualql.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gt2zkgdbpkv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2angbjtry.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gt2rngvgtix.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gt2dlxjdulq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gt2nhtuiesl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyopkyrc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2pcrqudpn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2eypmjboh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gt2wogxjfri.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gt2rmmzepfb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2iocfvmfj.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gt2qrltferv.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmptbmmo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2wvfojbid.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2fzelobub.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2nzzvqpcd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2voermolp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gt2kjjdvkev.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2zcmakdyq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2sevycbee.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2cncddivu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2zyznpycj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2oxzeprdi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lhkdoyth.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfkpwzwn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gt2sohuninx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2pukcadoa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2unljtgiw.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2iokjwcjw.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gt2zubwgjyb.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ophscgdi.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2stjncnbo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2uejriibq.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2qotlujho.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2mkhynfqe.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2yumltrfq.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2elhcvxrg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2cduovoaj.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2seummdzw.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2crzlusvn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2fwkfjvdl.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2zpczmtnz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gt2ftytbmjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2hdanrkih.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gt2hcazdlru.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gt2egmprwtk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2sleueegl.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gt2terjtohi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2fnujrmrm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzhrgxdv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2ghftopno.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyngdoku.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gt2hsdxouvy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2bfzqmyka.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gt2ynpqsmxr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gt2czliwexj.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2mfgvbbqr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2ffdxubiy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2hpudivfa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcsqrqqa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2bsjajvgt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2hinfhwwn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxrjfue.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gt2vkxbizln.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2corrpvvd.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gt2sihzezxa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2odszwlkz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2olmngkht.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2ubxkrywk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2uqmkowtn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqpecbyw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdwjklin.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2isblvhmq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzbwjapv.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2cdqhszum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggzuzmnx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2zsjecpmi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2tutigtfe.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2hfzclnbl.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgqgqngc.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2mdlyyhmy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gt2urdahrsm.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2omuiwxtl.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2ikcrbkuf.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyvfiekk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gt2eljsslta.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gt2akchcypj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gt2enbnsdwx.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gt2wrsvmgqq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gt2thqqwdgx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvtbylon.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gt2wixzeufy.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpyitrkt.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2ynmkbwpb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gt2ivfrjylw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2naoorcri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2hobngjvs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gt2jjwgzexk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gt2fxtspcbj.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2kbqlgqkm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2zsrvbead.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gt2xqqlfjzt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrlfobil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pocsuqrq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gt2daxiorir.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozcwzekp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydhpdkmy.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gt2mrgpoksc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnryvyim.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gt2wppdpzpd.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gt2qrnmoulg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2pdnqslgm.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2mmftejfg.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2mvekyddc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gt2mykvkbff.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2wlltgfjn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gt2ckyaatxt.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2pusjsupi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtejkwze.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2hujmekiq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2zmorhtrx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gt2osqeurac.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2avscethj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2cykinhdq.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2jpqwnkus.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2hajblbrc.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gt2xlqkprcy.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2bpkkjydt.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhwjuyjz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gt2arkqnqyw.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gt2kfjpoeor.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gt2tutqfpwd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mzileqjz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ahnoapku.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2hjnbmell.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gt2ljbrxyeq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gt2tfosehke.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2sjxynynm.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogzliofi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gradpgmf.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2awtafhfc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gt2iqasiebh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abclilgr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlcvsesb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2cixplkpt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2wpdoulpx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vffrgext.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2xzcnlhpx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gt2eiolprcl.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2klppjvst.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2rumrfitu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2chswpobe.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2iyjzhakp.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2byhvyawm.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2qqxzvjzs.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gt2fbejzufo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gt2qakpkxee.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2rzvxsgpi.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rneudgut.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2igdydxik.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2mxilmtrg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2kufrurzh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2woxtgulu.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2upetzjhu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2qbxjngny.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrjwfqyz.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cylylrfc.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2upareesk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2zillyvxw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2tpbgnthn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2brpsrgcp.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2wmfyiovy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gt2wctuyojc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfmaueci.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2xmtclrem.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2nvvywfxw.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2vihobvjw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2cgqcostc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2sqyeaxvn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2uhbqbrjz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gt2gumtgvfq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gt2pgreties.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2twdtpiif.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2wquenbzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2mjmsncqf.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2kdztthtu.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2sxwwmgeq.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2vvcdrejj.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2klgzunlt.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2kqbudgok.html


<!-- 参考信息 -->