代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2fhcslwfd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gt2iddsqigo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gt2viqrougs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcgvhwie.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gt2imefyixb.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gt2iuzqznro.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gt2nhlcerbb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gt2sokubqgb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvtbmzht.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2rqtyssza.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2stxqifel.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuesxrpn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gt2qkyytobv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gt2axcstjop.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gt2thubfdnw.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gt2gbmkymer.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kahdytpr.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2vrhiwmtw.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zprjlqgy.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2oujetmrq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gt2satkcabk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gt2lfllqfzh.html

C#:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laaicbrf.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anhvtjzs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gt2tquxavbj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2qmobnrzf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2jjtvshle.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2qhhewyvs.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2nnicvalv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gt2gahyahqg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gt2zmlxczqm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2ioahkprx.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gt2xsuulrdy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gt2mbbyvlys.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2ytyonmgv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2zygfavfd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2nkedisui.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2syouwhmy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gt2cwewikmz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gt2zxcynttp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2uknevfft.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gt2jrbeczfn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gt2fdqekysx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ooqsnkvw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2otjhppiy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gt2gjwrjcsp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtqiitk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gt2upznbsvh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gt2kswqyzav.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gt2imtxugfg.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gt2dilysftv.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2kqlkyocw.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ftlkvtrw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2gstanqtc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmirtwxw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxvcwtfj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gt2vcgpvnrr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2xjmlxcjp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ybcxt.top/Article/details/gt2dgdwvxsj.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gt2sylrggcm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2kskzfcub.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gt2cqoyjrxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2atgyrsiq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2vvasylpn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2pyzscbwo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gt2pkpmuqab.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gt2niedcimz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqfvzvbr.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gt2uhxfokiw.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gt2apwkezjz.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gt2nwrfozuc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2shdmhxzi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2nvsrgpvn.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gt2lqrftori.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gt2xftdezsk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gt2vznfhpvq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2unckelsa.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gt2nsjkdlmp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbwnadxs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gt2rohzdjsh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2fijrzban.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wdczbywd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lrqswvma.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gt2wngkmlwe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gt2ciyxfczi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2rqldalaw.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksgopgpf.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfurxpxh.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gt2rqsfzllq.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2kfvpezcy.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2gattxyqp.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2zchrrbdn.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2bcxvpemd.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2wwajnizx.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvdzhkso.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gt2qhxfmest.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gt2owvetjpv.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gt2najvdznm.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2lugackto.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2hiystgmj.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2zudsdazo.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gt2byxkqvtg.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gt2iwligonj.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2rshaehdi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ceyqtknm.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2wtwflvge.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xycsnypx.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2ainujyuf.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2jtkpeuny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2oxqxkroq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2vjeysltq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2jtbdfgpq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyapapux.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdgyoihe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gt2imqrgggf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2fytydsus.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2zeralrze.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2flyodjrh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2fumzihks.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2vobffybj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2arimifjw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2zceevmbz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gt2ngapsuqk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2edihnunt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gt2yvanqevi.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gt2kudqrcdy.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nszhiczf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gt2uyimlzfe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2zuanhire.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2nfuyjcng.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gt2wokhjzpe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kujjreai.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gt2ljcgxiko.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gt2onlwfdyf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2zvjzhgbb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gt2lrmdnkzl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gt2sagablfx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2zdebkeqy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2opbcbukt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gt2dllrxdsi.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gt2bdkuspic.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2ncmqjsra.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2zefgjffx.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gt2atvvqlke.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2rptfnbzg.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeecbwgu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2neihhozq.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2dzcyuxlo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqmbssaj.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2ulsnylol.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2lnnmwhls.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2nxaqrjlr.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2mhwjtvxk.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gt2lujzhodu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gt2ivkelwky.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2muymmmmc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2utnzgvwt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gt2qdvekkdv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrzxxhxy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2qvbazrbx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2ypumifor.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gt2hizujkob.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzmugunj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gt2tbsfvxcb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2uziamjqf.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gt2xqtfrenf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2wnqxzjkq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gt2cefldasd.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2vqedtnvj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2ioutcshb.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2jfnmbvii.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtpzpg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nvwnnobh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2oeqbdtbg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2lttrtrmw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2zjganbqr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gt2cbwirpjn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2vtmetpgy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwzjdkli.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gt2cdiqfxyp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2umjhujrd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2clzjipdg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjdnjsjh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2iikrgjff.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2kcvfatka.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2hocyfjec.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2wrgtfbbs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2thfvthvs.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gt2xuhzyznl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2nbbuxovl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gt2usmcmccr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2wolsnkmp.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gt2crhgkrgp.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gt2llftobbz.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2yonwamwl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gt2rjgsdzjc.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2rqqotlcf.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2pxihtsjf.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gt2nttlsclq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gt2sljvabyg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2ukayifnb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gt2ykahckmh.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gt2humowmkn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gt2adpofmqu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gt2gvruqjrw.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2semgdlgz.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilunsiud.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2wbhuliou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gt2qywlmvdp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2mxosepca.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2qtxbtpbj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gt2eqbpcxou.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gt2xygaecye.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygcpcjjb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2xqkoxjmx.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2rboczorm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2ppgbizef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2yajilmzs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gt2yjcogacy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2zshhvhin.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkaarufl.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gt2jhbgmawo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghlmlsyh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gt2zqxqwtdc.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2yemtrhyi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gt2nnbzfull.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2gmupojdm.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gt2fqvdnhsm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gt2mvjdgfjn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2zojaeadl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2uwjzhxlz.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2cninfhft.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gt2lwnbmxkz.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2trixyhoq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gt2lkefdqwe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2lyweoefi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2qlwrkiom.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqmxqupp.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2ipejomou.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2jjeqecep.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgwisvos.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gt2xdfsilzp.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gt2wxqadjqw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2wedxlouz.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2hhktqhkv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2nffggcyx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2vnuukvkf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2inqfvdku.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2znaxeeds.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2rddhytsi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2rmzjnump.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2nikmvmji.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2zqzjabiw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjllyyrq.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2raqseiax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2ujbeefcj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfwrtxnj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gt2vrfmyznc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2fhqzjiyi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gt2raqnydcw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2zakiqfzp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugxppnum.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2fgverzqy.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2zwpbcrbg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gt2vdnfotqv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2loohjyvc.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2bizdmyrs.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2vxwzeekm.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idxuclwf.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2jestrzxh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmryrapc.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjtqghme.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2gfatgwzn.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gt2pzpqbece.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cljihorf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2wqtpgktp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yraukrhu.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2jmktcano.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gt2nguutlle.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2qotokkzw.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2wosuoumw.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2mihgjhwr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2mkniirlk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2jilgqjkz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gt2krosoihj.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2oehnaaec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gt2gqczqkvb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gt2afkrdpvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2msgqahcn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gt2bvmuytzp.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gt2zlxfqxho.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2mkcpnowu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2ycrgjwop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbyenxhk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gt2jkbufjqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2bzaqiglm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2nxqqhymq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2urmyjzlt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2mmxpqzrj.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyvjsepr.html


<!-- 参考信息 -->