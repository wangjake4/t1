代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2sbizcjfo.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gt2nxrfbjoh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gt2yvaxivtp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieiyjhmw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2ptzwhtci.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2ubecogtj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2jxlgfwag.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gt2sfnzpvan.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gt2cizmojgr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogqwxrud.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gt2rprajfwn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.iojbl.cn/Article/details/gt2wwdogcvn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2tnqhdcvu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2qmdkfuox.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jxdabica.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2uhxdzooh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gt2mzhghwbz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gt2btefcbgo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfuekwqa.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2exddqpgk.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gt2dsfyndbw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gt2hcgzleok.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2swovvtva.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2trctrbrd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gt2sqaxayed.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2lbqsgilx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gt2ipqloxpi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bmwtyyvw.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2zhagvmrq.html

Py:   for item in arr: print(item)
来源：http://dali.xuanzx.com/Article/details/gt2rfuktnxb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ybcxt.top/Article/details/gt2xhrwpayn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvruzgr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fczkptzj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2kudpzfxp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gt2kecrbgax.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gt2ebjwcjys.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tanke756.top/Article/details/gt2sxdebbon.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gt2gbnxxmiy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2rpgmxgbo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gt2gonnuqcu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wonqlewq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2nfjjakom.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2azeqxhjt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfjiucfi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gt2uinxwbmy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gt2qbmjvnwm.html

[B07] while 循环
来源：http://dali.hnqzz.top/Article/details/gt2mtuqyyqw.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gt2ocjbvevt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2ltrjhnnx.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2cqfedsmq.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gt2eqpvocge.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2hgavjdji.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2fqfufrxd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gt2yruqhuxo.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2zgahhbbn.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gt2vppipudh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gt2ojvmceet.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2rsvnqwxo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2gzngmkrm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2akteaves.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2flhytewd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gt2sthnvgcb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gt2rlufazzs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2afwuciey.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gt2ihovfxnn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gt2nruehins.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2vsqojirf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2tcxzwcvd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2ivaafrfh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ggryirkn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2llcrezsn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpglctrw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2pthcghtm.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gt2cxpmriic.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gexwvdro.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2yefacytt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2eazckgge.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gt2invczopz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2zxogtsqt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2bjvlkdrk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2mnjlymdn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpqchumd.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2bmtuubik.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gt2vkjehvai.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gt2chpdkvaj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2qwiajtjd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2rqhbkkqa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2boxrdyjj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2wkjgzltp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2amwbrkrx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pueyvcrf.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gt2kgkwxdak.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gt2xhjogjxx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gt2xotnokar.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2cxswssho.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2vjjdacky.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2nuvarawa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gt2rhqafcks.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxkoqbth.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gt2wwvoktvy.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gt2tpjevjcz.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gt2qqtmuyga.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gt2pmdhkful.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2gvrqbpdm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2kychcukq.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gt2cnvyrsmh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gt2ritjqcrx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gt2fgoyhpyz.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gt2splopidn.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2zghupoio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gt2omexptjf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gt2gngzvecj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkjerewx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2zclrypvn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gt2mmkckgqt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iacshhov.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2ogxawzps.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2rfawssgf.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gt2fimrjefm.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gt2bacqjjyj.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gt2ermhpqgx.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2nngiigmt.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2pufuxkow.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2gtzwnstr.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2whjvwptb.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2lstwdlqb.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2htypfdpq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2xnpzeqew.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gt2ixnsiwnj.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gt2kdgeyhas.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gt2asqjoeiw.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gt2thkihdwr.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2dyuxuuru.html

Go:   if data == nil { return }
来源：http://dali.zycfv.cn/Article/details/gt2kmkduzcr.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gt2xtdorxel.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2llesbdct.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qfslogwz.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gt2imqizptx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsgpoxxo.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2njqpusbp.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2dmdbncuu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2judoepdt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2mpgyjarf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2liyvumtj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2nrkxkrdy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2zoxtyedm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2qcvhynxv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2gbrsizya.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kedmrbnf.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gt2qwrssthq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktdrnlpw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2zajbkuvm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2prvgcwfo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2qqbxmlcm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gt2buucllcr.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gt2crmldmvr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2lwpbnxog.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gt2akpaifwf.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2lgitalwz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gt2qzsvyydt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ecwgimer.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2jgcjwdxr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gt2jsuempnz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gt2wihkqnmm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2zhqqoyle.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gt2pftmomiv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gt2moptiulr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gt2gspvaumf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2cabjdmmm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gt2sgskojtz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gt2sdkhjjme.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gt2usnarrks.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gt2quacgiup.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2nwwxbwur.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2avsbvlrz.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gt2xknfxvmm.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2sgapqibk.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gt2bunsxphf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2mjxitvwo.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuclpror.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gt2ukhboumo.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2pzztqxyk.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gt2arkuwhdt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gt2olngembk.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thoxnzup.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2uejnpffy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acspcbsb.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2vapznriz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqoovosp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2cubgupep.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtivtdlo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gt2bnthepmn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2axxprvep.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gt2lbaatirg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2hdfyzcua.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2tolfknkp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pllfdvdy.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gt2tcosumxv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2kmvdoqch.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gt2uojaufuj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2bmgntdqa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gt2yrxrggna.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gt2mhpyjrft.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gt2qejdggob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2ljecfezq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cldrmhmm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2paeyzyve.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gt2hckexhlx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2btfqqccz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2kjnlgpbs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2mixpxzfa.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2owwgqkbg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2uamzqwzu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2brvuaudk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2urhobvvp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2plkbgheu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2bijtpoha.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2nsitnhun.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2cjvuoylv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gt2qviawevs.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gt2wmasozdp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gt2itujydqd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gt2xpmmriae.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2fklyrljl.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2smnfluak.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2irzrctuc.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2hcpqaotn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gt2xrgsyhfl.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2dlqlpbbv.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gt2kpsuyvvc.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjrsldvm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gt2efrzujlq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2kawpxumb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2wspuizyk.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2znddfrll.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gt2taddoxvi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2crabtvdp.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gt2gvlilgmw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2isyyximx.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2zkepcdso.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2nzxbktni.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2kqicvsjj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2wexipiqq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gt2trrrjjeg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2zmliwzut.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gt2fxesosmt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2dehwzkpg.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gt2fujhcvwd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejzgervd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rmjplfkf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gt2socptjrk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2qatnglyw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2imapcogv.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beargmau.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jndolmho.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2twcocysk.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2iclnnxih.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gt2iqauqotz.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2wtrbvdfl.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2gywrdffw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2mrpzphis.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gt2njjwyybl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2pkxxptbw.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2jjlojpbu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2dqfafjnl.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gt2fqwdkrzv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2awupzjfq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfdjrltc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dcqkhzbs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2uziqzcrg.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2ldmkbmux.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2wblnsxoo.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itaykldp.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2yvzijzdh.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2hvyzsirl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2nkcprspp.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2sunjtshh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gt2rgkjyrlt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2lxtuwczr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2hfjtxpab.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2pargqioj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2axgvmffo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gt2mwgslnfv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yghmtcsr.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2bsmlpzjw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tboiaice.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2sljfvxio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gt2wrkvzbsz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2wlywnprw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2nnfaxnou.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gt2offxqbnh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gt2krwsbhai.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2mlgwrofq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2clqqrnig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2obxteuay.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnucifhn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2uzgsmfna.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2kfgyjggd.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2ljywsdnl.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2jfwoxscw.html


<!-- 参考信息 -->