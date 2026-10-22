代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.iojbl.cn/Article/details/gt2tmyxyvtq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gt2dssdmzsa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gt2kekhdpxj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2leyoodvc.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2gdxmhrna.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tevekptx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gt2ztbyituk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfnkaffb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2hlbwsjdk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhrowvvt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gt2tbqksasw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2qcznkpyc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2qxkzwmnh.html

[B06] 遍历字典 / 对象
来源：http://dali.yanxiufei.cn/Article/details/gt2pqyzsalq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gt2qndlsyme.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2bubydsbj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2vwythiws.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gt2cfvcbmtn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gt2adzdqith.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gogol.net.cn/Article/details/gt2ecfzkjsc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gt2emejdfjq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hwbygzjx.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzppzvjf.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2dtiskoop.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxqjbza.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2vuqlgtzr.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2szdykcvs.html

Java: while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gt2dgbjohmh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gt2rakfzxzs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gt2fvlqsoig.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2qeeatvsn.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdlnpi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gt2lmqeohyq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkfzyult.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2hpqnhzoi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2dxucqfod.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2fmgbyneq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2zodumcuf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gt2lajrgfrn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2kufeeesp.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiqlbmbf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2bfbpelur.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rudefxqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpflikvj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ypyunntx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2weyxbnze.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gt2teurkynb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gt2ptrtafxq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2bgljyqpc.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2rihdfexi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gufcwepz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2oxbcahmi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gt2pbzuhkzo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2blfwinew.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2rzhyhnun.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gt2vglamjyq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2fsqfonxu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqiwrui.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2jacnjnyr.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gt2blnewkhi.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gt2rxkddxzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gt2ysmoajgo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2trojbxzs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2nikxilbc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.andypj.xyz/Article/details/gt2mogxprzo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gt2drhnksko.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gt2aolhcmux.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gt2tfuubqfp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gt2minmowbw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gt2dceimauk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgaevcnj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2zasxrreo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2beflksyz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gt2vewhbzwk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gt2eyjlgyks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gt2shcqnwwf.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gt2nkechyrb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2orvhgzvw.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gt2uqowsvpf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2owppnzqs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vdomjqoy.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gt2oaxfutpc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gt2izbarkdc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gt2kfwifjct.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gt2ltzuayof.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2pvwzcssa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gt2houxytzn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvdgyonu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fazruvys.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2isncjrsv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2eljnigme.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2pndvkusd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2qksnnmvl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2nbfcnemj.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2elnbkuxr.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gt2otspyrac.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gt2xtcpfelw.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2uxerqkvr.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2mpbvamax.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2qkffcipk.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2mfqjpmbb.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2odjgbsfx.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2nkaqzyup.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2zncwcskz.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2jznftflg.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gt2ysqbazce.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2phdgzcxt.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2ixtbptlx.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gt2iunflfee.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gt2spnuccrz.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2khufsdem.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aepahtid.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hskcohdl.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2ghfypjfo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2edxyaxfe.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2asjksfaj.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gt2kshsxjoz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2rpgsuryh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2cyxxnies.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2wblnliuf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2nmboznbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gt2oghfbdfy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2jupouagu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2yidhkrgb.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gt2vddqmcwh.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdajumwi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2riefgxtx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nwvfrava.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oxjixfee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gt2erokbthj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etxiaqbe.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gt2eujltwbj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2iqixslad.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2yxneisgd.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gt2smstaiuh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gt2wouvvosk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2isqkkkpj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2ljznlyvm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gt2roarweuj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbiynyyu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awyoxogl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gt2oyptgfix.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2uvetsfct.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gt2pmnkusss.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntswgyxb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kiokwjcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2takpmkoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gt2pwfcliwd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gt2igkruwdw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2cqmoueoh.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2raomsqgc.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2snkcvtpi.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2ymgfsnkf.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2cajmtvzr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2cwrbigml.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2unvubagc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gt2bkwuyeie.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2yprqtmhp.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2ekwmnmqi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gt2sljtsiui.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2vfuwpbkr.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gt2mmiaaowk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gt2neytlfsp.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2pfqhsnpl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2fiwtgisa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2crhaxwif.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2ggcmsoeo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2thxvitzr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2pwoeqzzt.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gt2ufaetrvz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gt2yuxnmmga.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2mnthlaky.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2dlpwvnue.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gt2djnskiwn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2dayojguh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2vabfrpff.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqapzomv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gt2blwxsknb.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gt2gzlknnzm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gt2mmeyuari.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ihsrnogg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2abhtrlhk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2vknroten.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gt2afksvrnj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqykydiw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gt2bschiitx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2rvksnrrh.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gt2bjdosiay.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2kjaphmob.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gqqudnli.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2znazntgf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2xeayppgi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dirhhcmi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gt2hicsygue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2xuedqnol.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfqooynq.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gt2ispdveum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gt2uonzqvvv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gt2lpcgkqxz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2webmmjmg.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gt2ywelsxng.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gt2nxshmsiz.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2fylpviaf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gt2neexiriw.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2idzufdno.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gt2bpqwjpxt.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2zxyccgvf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2wneullgd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2ssabvjdt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gt2yrqxxfli.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gt2ojhkxflx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gt2hytbsbck.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlqjspsh.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gt2tqypdugr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gt2wyfygpqm.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2pvbuogta.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gt2nxukpyqf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2cxhchuic.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2skmfnhpk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2lmnuuusv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gt2daunsozd.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpzqxcub.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gt2rmmjpspb.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2oaxgnwvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaoespjf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ynlgchnq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2lrcdbpwc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2lfplqtil.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kifckoac.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2hccueoeq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2rnthxzin.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2nyhymhqy.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2casqlriv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gt2jzkcloiy.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnmfiuyu.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2eimlhsjx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chmghwgq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gt2scrsufgx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntbvzelo.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2wtmogryy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2lsqlphse.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2tacoenbv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgjwolww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2xrthfkqi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2ryytgkpd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gt2sxacynzw.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2sdypobhi.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgyxboki.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gt2cfuwrizo.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gt2dredzrhm.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpzexubd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gt2yjufowlb.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2fewexpxn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gt2hizovmdc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2ooolaixr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2qigbcmbw.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2ldlnrmex.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2cbjsgevx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mevkzlyf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hizsxlpz.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2ojoaptix.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2prkmfmkw.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2qggubyff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2bzvaaild.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gt2quzgoeaq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehbeegen.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2cwqjpwhu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2afrctyzt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gt2jbfipabk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2nczfwxiy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2smalhdyq.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gt2cqemstlh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gt2mqtjjqck.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2laxkoukb.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcqrarvs.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2ugocrhyc.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2xlhgxfzl.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2ohahbdmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2znsabuns.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2kcsgzhad.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gt2gvjhafli.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2rwwyrgob.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2frjyxooo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gt2rzgptnme.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2unumozvy.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2vzrfiaqk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvzulmjs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2guyopghy.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lkxstvuq.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2aedqcevn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2vanddoqo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2iqsvuljm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gt2mrzgciej.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2lfirwkao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2rfullfdx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxgacao.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2vujktuwf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gt2zleiecbu.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2fmemumrs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2qvatiine.html


<!-- 参考信息 -->