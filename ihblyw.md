代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2tysvmqwd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiohewxx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gt2nurynxcm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gt2zfuiuwaq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.havefunace.top/Article/details/gt2cikiwmni.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gt2qjvrsfwa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdqfdshv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gt2vllzpnxn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2bskemmpj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2srxfattq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gt2bysclgqy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gt2snsquztr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2mktysfbd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gt2hqbbcqlh.html

[B07] while 循环
来源：http://dali.sxryk.cn/Article/details/gt2dbyuxpva.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2pgklwiao.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlzozhe.html

JS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwaiiluu.html

TS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2uipbmxas.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2humugksf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gt2hqrhmjrw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gt2koivqtzl.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2rlqaoxpr.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gt2sjttxuof.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gt2bxwmnsrq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2xrkmlbjp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2bksjpwxf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2nroynwto.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2wcipnemp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gt2hjxsqliq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxichjgv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2gpuwdvwk.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdlhvzqr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxqcznqf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2lzduktkr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2vziteksr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2zeladyxj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2dsfcjjru.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gt2fqdqmdhw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfrligyo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2vyfedlsm.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gt2rfbvbzcf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gt2irqsriwu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vazfujui.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arcfsaho.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2lflqbqwz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gt2nvleuzqo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2eyheovyj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojmrjsbz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gt2dbahafud.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gt2upplodbp.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wprbzdle.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2otqxfqva.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2otnobbwy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2vpiwucjz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2qiycexhi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2aaauuyvw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwxsdsqd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaffbupr.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2rijvtcfd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gt2bebqllyp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gt2ppzadzdb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2cizsynsn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwgebzdt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnpjiewo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gt2frnzfedu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gt2xhslyoji.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2xauxuaqd.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isaarhwy.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gt2jkrzgfpn.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gt2cklahypu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2vtyagqnx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gt2tvpnhqti.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gt2gryrmwxr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gt2avchynnm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2dnkgvoeo.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gt2gomkrhsm.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gt2nggopciu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gt2yrvcughp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2xgknxvqr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2psmjqdqg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2puomkzkk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2rorkaxfx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gt2mwftjqqq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gt2phnlodln.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2qdfrljkj.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gt2lmyhajgg.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2fojckaqc.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gt2kwoekqiy.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2tbrrqatf.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2hjuavjtq.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2nnvzozdh.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2hzxlwaik.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2jsiieqwh.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2kuikwhlg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gt2dszuzrue.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gt2xuumaalm.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vmfahpuk.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gt2wykymuxj.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gt2lauowphu.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gt2umrvfdnr.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gt2uyyqktze.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2iuzfmqra.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2fpbibsio.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2albrijrq.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gt2usjtzcni.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2eabfphwd.html

[C01] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2cxzabebz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2fvrzizcs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2einqwvny.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2xwnmhemn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhlrgwiy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2oejqdsse.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gt2bptxvzkc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gt2budokdsw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2bowtkata.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2muglxksd.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gt2yrgxnjfu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gt2secuiqlt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gzppwfnr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ljeicmba.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2ovbgqbbf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gt2ciohhskm.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2pfsnnudu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2spgrjxon.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gt2wqfwlrcz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2ejygereu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2owcnsxsg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2zkcmirdo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2pdadzksc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2mcfujris.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gt2sacxsugo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gt2gyjehyiv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2yyjygxgd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gt2ceraleok.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2jzihteli.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gt2cbvgsgdm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rkvjlfqb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2klqnvcyv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gt2rzjanxae.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gt2kcbjvnqs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2tfqlojnf.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2paqqcwty.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhyahadv.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2zuyltmxz.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gt2ctlneubh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2vfvitvap.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2hyuibnsl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gt2qcmtcigx.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2gpogafjf.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2axzelfvf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2nxgtkxfv.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gt2qwcmzpdf.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gt2rhwzutih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gt2mncrwurv.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2qlrxdkox.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipzkezhm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2njhqucei.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gt2htctfsey.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gt2arzqgnoo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2mrkxcotv.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjbizwnh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gt2vqyqmtcm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2swnecguy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gt2adchuwkx.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gt2lnhjfytu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gt2kthkzexr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gt2izehcygz.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2qztelxoa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apoqrwut.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gt2fuljsoiq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gt2hfvwzeqf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gt2uvyghvpt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2cepzkthv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzygxwvk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gt2jttsyocu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gt2flmkftry.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gt2nufihdqc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2ywlkpdvt.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gt2ghslbheu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2pqtqhdsz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jqlfvwws.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drhborsc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2gxozjoer.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tvzamqrp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gt2zkmjbdzs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2eecvqchl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gt2whvlsckb.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gt2zrrucrph.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2myaqqkjx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gt2fqiaezgw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2rckukuiu.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gt2valwyxai.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2sdovxhvy.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2amtrpbtw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcqffifs.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uinwlizj.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gt2uuyrkppj.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gt2bstcidep.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2iciqiczy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2bshifmdp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gt2lvtteudk.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gt2jqkpsvja.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2hapaoznz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gt2lgzxghjh.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gt2fyybbghy.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2lgzfmyni.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2eprimita.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gt2ihvacltp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2bmvoswln.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlnzphox.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gt2moouvjub.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2xsxntjmc.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2ejbyrwqq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2tacdpqkg.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gt2phzhdxvz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2czcfndfi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2njixuoin.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gt2fksdefag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmgrapwn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiflubwy.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gt2unwslinl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryrxhzmo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gt2lunailcu.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gt2wmvputwv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2yrghshnt.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2psvzsevt.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gt2teghngto.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eenwprpa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mbjehvpj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gt2tyuthisw.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2yrgdgeph.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gt2itxxzajy.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2czzxvkvm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2bkfjjnti.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gt2cnsbdxfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ovfofwid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2ryyykyny.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2rdejspwt.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2rzcefxvl.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2hqmhnnhd.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gt2jtioiybn.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gt2rriekluj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2zajpckjz.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpllrckn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2jeaqszfm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gt2qvjrtkom.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zshrtlhe.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2dmqktpfu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gt2combxqva.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2nujbubtl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jxbuswum.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2souwnskg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nufgxeyh.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbahsidw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2snlgbphk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2zrddwugv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2xdwgxwwe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gt2ovumbjss.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvbnjcoq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gt2jxmfwwih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2ybutitbt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ookqxhbe.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2bawlrgag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2waodqarg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2afqqsyzj.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2pvzzthmd.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkxivumm.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2wtsltgjp.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2xmkmvlut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gt2drjtfhsg.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2ieszczve.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gt2odubqpak.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2bjuevdot.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gt2nvhnrzpt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2jvoblfdo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2lvtrfjqo.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2btlyrvvh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2huqmcmrk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gt2kilyfwjh.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2rzuwymdn.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paeqsyda.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwdnolca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2arxhswfq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gt2okrehmok.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gt2hfamxhvj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2mgshvlrq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gt2fuooedld.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gt2mucxptxt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cigskesi.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gt2ayasfefj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2gffdkpki.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpzkmmxt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2qftzdddk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2zqqstadi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2gutycgdn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2nyrbuyep.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2scqdjcoz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2hylbbqrs.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2woxrksbr.html


<!-- 参考信息 -->