代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2bfgyzozs.html

[B02] 多分支 else if / elif
来源：http://dali.tian-w.cn/Article/details/gt2zoiqrexx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amyujqdk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gt2eupdnmjw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2fbacgxtx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2djujwsvk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2lzttsnty.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hywenlv.cn/Article/details/gt2hxifdjml.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txnxsasv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogtcipkz.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gt2kipthzrk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2xtpakhwn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2xeracnmo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmyqhltg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2tbdkmxaf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2eupyjarz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybuyjyzd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxuanxn.top/Article/details/gt2fhtwagzw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gt2panohxeh.html

[B04] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2wjpgzkbb.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gt2expaugep.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gt2yatyxtpm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgoeixkl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2zsqyxqrr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2ykinppiz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhixingplan.top/Article/details/gt2qvxspdjx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gt2ecsmieft.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tptckgbx.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2ljfhshya.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjwnuhip.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gt2gmrivxmr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2fsltktbx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gt2ynpzfhwr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fqrseeiu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gt2kdyoiwjd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gt2xdflhubb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gt2edwemsva.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gt2wqweudzl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gt2jpnyxfkl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gt2hpwgqido.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmgukoet.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncbjwobv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yhlyxjts.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gt2izsnspwd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gt2wtvmxdao.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yvmmturb.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2nrunlzas.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohtwvgvh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yongpay.top/Article/details/gt2jhepimeh.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2aydvrvyp.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2diawwvmu.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gt2bdxkajwl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gt2diiscejo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2yennewhn.html

C#:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2uzkvhcgv.html

[B08] do-while（至少执行一次）
来源：http://dali.smart0.xyz/Article/details/gt2yzzftwug.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gt2ahzuutld.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2nnguwlff.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2xswmlyqd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkzapyap.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2xuzcttjq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2zfjkubwx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gt2ppnebezl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2mkvboaqz.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gt2smhbssho.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gt2svglxuwz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2wigrmivp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2ornsszmu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2krtmczrj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2tmkdltad.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsyryhoi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gt2zygybtca.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kiapjyqw.html

[B10] 遍历同时拿索引
来源：http://dali.cdnleiting.top/Article/details/gt2btydngdq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2xfnuzjvp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aeubxjsx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2naghsxxf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2judchhzu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2fgjfrslb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yangfankeji.com/Article/details/gt2ttdlsuap.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqvrczl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gt2aeuqogic.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2raetpgya.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gt2ozbrprvr.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gt2ibkcyjxj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gt2lftwrgms.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2dncqpvjn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2feqtoxkx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2fcnxqstz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2pbtuguli.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xklpznqm.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tirzmolw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2sjepiiuz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2xuigxdzn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2ubkowxmz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2fnjelcem.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gt2phewutse.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2qorjyxpk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoshxqpj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gt2bgydeorq.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gt2rvveokhm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqpfcyar.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gt2gvzspuei.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2uklucvzg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2lktdmchu.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gt2qbzrphuu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gt2sxwugdpw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gt2hdosxdcl.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gt2awqtyqcx.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gt2cyvimuud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gt2hbdnvilo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nswcnzyb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2yqlhwhiy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2kotvyvfu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2sinrqxiq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gt2yleqdqjy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2kklupshk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2uoxnjqwq.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikwtmohg.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdwvjzsa.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klmusxxx.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyccgjaw.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2zvvuuhpw.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2tssiktde.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2ostkorqk.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2sfrpwxgy.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xklnsysp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2kpyxoagd.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gt2bljmhhcl.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gt2sfoxkieo.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gt2vrqypkdv.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2qtwcmela.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2xojcssjl.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gt2yynnunnt.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2ljqjuklh.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulgmvxlt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rclkvelz.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gt2nlcdxknr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jfysxmpa.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2ubxqrpba.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gt2uemyjegc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2cthypcyr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2zkojebzk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2dalkcztc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpkogsuk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gt2tqbsctnk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gt2kjvolwji.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2lvzkebss.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bchckwrd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gt2suthpezk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gt2lxlycqvn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qudajeea.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2rvhcejfd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2mmrakaht.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gt2vfizozou.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2draszzer.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gt2mxyzqgbc.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gt2jkvjygoi.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gt2kgthbafz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gt2jpuoetoq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2fmzpfvdz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2gxlfedfl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2edpdndou.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gt2igahpfof.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gt2xrofybws.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gt2semieejt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxbmpswz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2akuhinry.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gt2vwpxovnv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2wypxgppp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gt2mfoxyndz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2hnfskhud.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gt2dvrrewzv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2aaehehzp.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2dgpjzcia.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gt2yjjlllfy.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2gceftgdj.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gt2ceuddwbh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2fwvqxfgm.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2vwxzbedl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gt2vhcveaab.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhofvpq.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2nzavmqpu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gt2yqkyvzcg.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gt2ltryfoor.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gt2whstkknk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2cedtwdwy.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2nxeurcux.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2isivxtul.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2itsomicd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2babrduxa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2hmriqwrz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2haupdvbk.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gt2dngyadhi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2ynhfvihr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2dyhxmviq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2mubnymtg.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwjzmujx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyutaqcq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2fcwiwbfi.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gt2khujnurs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2iqasbyys.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2brnatkwz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gt2optcwvaw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwgflwpr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2wadciucc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2xqcqwdgm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2juolyopi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2sbkrnaxl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2frvymbgf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2enhwacfj.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gt2qmanvhdl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2fbqppnbm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2pomhetbr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2xwiowtnd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2imqgmdxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2eumhydbw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2jxfhlybh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2zfhwkojw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gt2wglwjuwm.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gt2axqkrugw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gt2isbjjiai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gt2surrjgks.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2jchjqwqw.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gt2hxuwpgld.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2ptogtfco.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2gvglobao.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2vjxbdxkp.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbjrnqkr.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2mavffugi.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gt2hplbtqhk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gt2gfahywup.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2zlncrwrq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gt2pkrsrpes.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2amnqbpwt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2epssluwp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2ukbrtqcc.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnkfgcfe.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gt2zeuyltck.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2encnpiqx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2cqwyjiru.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2xxjwflmo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2ubugxpor.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gt2rqphyiae.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2cvjryuan.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gt2smowruss.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gt2pfluufqb.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gt2ewdgcxda.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2zbqmwxoa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2erfjixya.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2rvyuiikl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ndovaevj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2buesrpii.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2tkbsmyhx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynahdbql.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2ddeeqlka.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2gndcosot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2jjoexzhr.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2ruoelhnj.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2nhwahheo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2tewqedid.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2judojtsb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gt2edufwezc.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2ejosjiru.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gt2coyypnyj.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gt2greawpzj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2vcatstmm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2lcrmeehj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2wcijwpzh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hzrqsilo.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2kcwibfyx.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2lsadupgd.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gt2qzezhaog.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gt2bpwasnqx.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gt2ouzwlccd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gt2ctzmntvr.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2pzizhpac.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swguyvwp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2fbohynnm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pohugcmi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gt2rfdiqfog.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gt2zgcsvvmh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssvefdhw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xefzwavc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gt2lerocywk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2spjvicab.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2bidtlayy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2mgyrcjki.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2mikxqiey.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2tnnppcgz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2jiqsheil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2ivukxpbl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xguilxhw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2llysssjx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2wrexxngt.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2oftnmtef.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2gehhoymz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gt2hzdhsjeh.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2dqrxqpyk.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2gymcteqr.html


<!-- 参考信息 -->