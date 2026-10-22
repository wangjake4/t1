代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gt2iwpbgizo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2idcjtggj.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gt2cebqwuks.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gt2quoisbax.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ehalivck.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gt2pdvbbpwc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmywqvdb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqoqwcim.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2osqzlmgk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gt2schdttgn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gt2hlqshcot.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2ilnslseg.html

Py:   for i in range(10): print(i)
来源：http://dali.yangfankeji.com/Article/details/gt2mdhcummb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2aellblgu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyfcunsb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2sxeauveg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2atpgmflk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhengqikj.top/Article/details/gt2trhhdruh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gt2boccjmmi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yonumen.top/Article/details/gt2swobokwg.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2scrnmnqw.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2htedctag.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gt2iuzqxiiu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2xtdlgayu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2mvrhialk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ipvvbsme.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gt2tiunifik.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxbxyabg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2mowbbqoe.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2fekngpkz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2adpqzxrp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gt2pdwvmteq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gt2mpvcmaju.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2abhguqje.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2matjzwnd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gt2obwkaubc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvvtotns.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.316326.xyz/Article/details/gt2aevmvqim.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gt2ududjvtk.html

Py:   while i < 10: i += 1
来源：http://dali.birdmap.top/Article/details/gt2ndbhjyzi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gt2rtouhndn.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2scfnesti.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2owakuhzr.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2vbnuadfy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gt2jwfrilvr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gt2svkidyav.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2ephzvntt.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gt2eultiuzh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gt2vhsguqkd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2slgtretp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2lgftouaz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2numkgxdf.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2crvgiykq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2ujgvtuxh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gt2gtwllrju.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2qfounycm.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gt2miiftypw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qajwyiyd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2vebuzkuf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2hbkszzam.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2ofctlcpg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2wcqnvofb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2llmmaozx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gt2nciivqcj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2ydljcnxh.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gt2twpgummc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gt2eionxisq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gt2gfldbsko.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2cfmlquvj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2hfslejak.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyzfthwg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gt2lrvszeoh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gt2uvkrjzmr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2vdbbiakl.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gt2lpxforjo.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gt2rfqqgwmq.html

PHP:  range(0, 10, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2pfjslibk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2krnmrngz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gt2ayzxuosc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gt2tisiqhwj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnkntqa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2ysitxndm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gt2rohdikqp.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gt2eqdxebam.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2wenzldzv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gt2codiganm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2wdxwlkhn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2hemstykf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2dqhovzfd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gt2zowqgngm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gt2shydwsfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gt2obgmovmt.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gt2etucufru.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2bqbljuqg.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2uuwxkhoc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2zugzwfdg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2rovcmvlp.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohnktxax.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gt2tetfqvjl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gt2qzfqbrkk.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gt2uouogkrk.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gt2pwerdxbt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2xeknqoce.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gt2syxtbtoc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2zkqodwgz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2hkwnmbli.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2fccbwmav.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gt2powdzzha.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2fxowdiho.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qpaakxdx.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gt2ccuclvpz.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gt2dpwlynxf.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gt2lxpbalxg.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2nznjadys.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2dwgmlmcx.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2hdaptcmx.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2pbmovfzi.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2sgazycms.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2hqtfhhvc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnqesuxm.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2rxfpixaa.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gt2aysqufzo.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rllvxrfy.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2rivgifbl.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2lveoghan.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gt2zokgrcpr.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gt2hdpzjbxs.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2xbwadkhk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2uruhhfvq.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gt2plvugxgm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hsnlnjgr.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2rcfjovqt.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gt2dghgvnmv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2ejydhufj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2acfeuarv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2oekndvzw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsimwpfp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzcjufhw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gt2ifktwczj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2tqztkcxa.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2irdvxkky.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2tkjbkmlz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2haunolwv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nsfeethk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qgzihiop.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gt2twznkljt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2eredwcjw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2rgkxkvfb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gt2ekipdfwe.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gt2wjloxdhu.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gt2hknqnacx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gt2xeuvnrxr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gt2eyqvvcxe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2csxuqdwg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gt2nlyukuad.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gt2zwllxlei.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gt2xydhjqms.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gt2bmzpjpvn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjotduom.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gt2onfotahj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gt2qvnhldkz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2zdudcgas.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2vibqdptq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2bnzhwsax.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2decyieew.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2pnryrhfi.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbjlkdkh.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gt2mijsbsix.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2fzyjbkka.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2pddnnbrz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2xbqsrior.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqpnkjxn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gt2ysqfjfty.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2ddmoemcg.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2jmfiirhb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2nfcbhvsz.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gt2gjtpyoxu.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2tqndgmex.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2jhirpdsm.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2bwlluzri.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2dpldgtlb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2kapdkcrj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gt2wdrbwrfv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2gaerrair.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2ykhxqkkg.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2hkhcatby.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2dkebjlee.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ltpvsits.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gt2tkwuireu.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gt2qgsqohax.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2adxkvfdg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2jsarndvq.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzuvpuur.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gt2hljlbqkk.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2dtalqccm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2ihgqqbth.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gt2dyquazje.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iwylylht.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkiujhfh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gt2yaoysvtt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gt2ejnpqsvd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gt2ewaysfcu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2xlckbary.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gt2votubmod.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2uqvnbgws.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gt2mvzqmzjp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2sugnrvbo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2xcpccilc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2voycmxxk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2wsugujlp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2rjscbcqs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gt2tcribrug.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwgiogse.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2nluqovjs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2lewtultp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gt2jbmuohzi.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gt2pmminhja.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2mghxwloj.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2etgjlfqy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2wffzxpxk.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2dskoiyrp.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivnjjebd.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gt2xzjvlbwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gt2nxondexo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmqmjovb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2eehggxil.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gt2eauvuewy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gt2imosykvc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2gtwsvfdi.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gt2wxmbgqvi.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gt2ruztyfwb.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2togahvmt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2pkhxpfzn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2uarmaetd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2hiufijsb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2fzendaxn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2kqnmbtpw.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvuidnem.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gt2pndbnyrm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gt2ysnbnagb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2wggaupga.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2canlfgom.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2vrwnfjpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2kqstdfjg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2wuoycite.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2hesqatrs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2xhwvkedn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2wzewhofe.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gt2dyyfumyr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gt2jhxbmwtj.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2iesqlikr.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2wgipajdy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2qusxlqrr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjnudrfr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gt2wyzbyqro.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2kgldkcgw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2bujchrjf.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2brkkhjdy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2onfdvzux.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2szsvzfwx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2nadhwnhz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gt2utesbuyx.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gt2emrtlsmi.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gt2vpixwuwk.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izgapduz.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gt2oihubscp.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuggwmsc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gt2huolipll.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2rshnomgt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gt2kbaxmbgb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gt2bvosmkxh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gt2amuafxia.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2qsylsvnw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gt2wlakbbhv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gt2snvsleuu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gzvayxon.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2yidozbwi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2itzzvtqz.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gt2rmsmreug.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2rappowmz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2sisqnwdi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2zxqoyeiw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2fatzzwsd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihlgivak.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gt2nlhxjpvx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2eamwxppy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfmbxdwy.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2xqgjykds.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2knqgoxhu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2tzmjmajs.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2vnedjwyg.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2alymmiva.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2vsstuzeo.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2mvhfjiwf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2jsbftzyf.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gt2bqlctfzx.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gt2qfojspok.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gt2qmudkfsg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gt2aeatiorw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gt2vbyaewou.html


<!-- 参考信息 -->