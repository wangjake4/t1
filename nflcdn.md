代发 wailian999

[A26] 类型转换总览
来源：http://dali.aizwys.cn/Article/details/gtewstelyb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xinyue.icu/Article/details/gtxapzaler.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtvakwrrpe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gtjglylfso.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gtvxcikeqr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gthkoaigat.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gtehmymmie.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zdqjudy.top/Article/details/gtmcqxdrdt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gttxyfgips.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcyxqgtwn.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtghwycimg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuauqgvhh.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gthxkfwitg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gtjaitxckv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtpfwtutej.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gttevqvfvt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtwqndrazb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtvbplcdic.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtfypbdrmb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gtjketxxqd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtaxbmpogp.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gtzjblfuvy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daxiang520.top/Article/details/gtrkzlavem.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gttnwlntam.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gttnjgyayj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtjndplpgs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtvtldflye.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yvedp.cn/Article/details/gtsttxgkix.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtentmgvxq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtifcrshkz.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gttxyddaiz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtcecodtto.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtlwsoioog.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtdrsigegs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtklhzfpob.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudtzcysi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtjevrfoca.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdroicxup.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtmwzxuprg.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtwgyrmsce.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gthsnnxpzz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gthqpovmrl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtbitihlus.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtjikgbkqj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gtfpwctmoq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtcxcqxgds.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtcvmifmgp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gtddccivze.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtwyyplcra.html

Py:   for item in arr: print(item)
来源：http://dali.guannengcc.top/Article/details/gtqnwahzsj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gtbzhejneu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtwylbdheh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtdknhsrur.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtqzuwpurw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gtmqhonkcb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahqwmwuj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtghbvpuhz.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtkdidzaae.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gtgusmdauu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvskijbex.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gttsxsjdes.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtjmattviz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xinyue.icu/Article/details/gtgdmsqaia.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gthhideknv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gtokbkepae.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtczvniqwj.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gtzotzkelg.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokmhzqfn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtthliflcj.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtknauahcz.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtslrxqknk.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtwnsxngun.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtjbuqxnvs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gtkeagxpbm.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtnndrnlcn.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtixfyanfb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtlrhbtfct.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtruaozmce.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtijvyhsko.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gttegemuum.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtyivhuuoh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtjuwcdlgn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtgajybfnr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtblxtyppq.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtdmgcjqtb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtwvmqcmcc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtfdyiqkpq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtrglumapd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtmwumrnrw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtpradjoqg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtnpycesud.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtkwiaqllm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtvgbheqmc.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtbqgbhwda.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtufmfawqe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtdtvbmghc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtroipgbkg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtcahksjij.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiorsmlot.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtryufcluz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gtqnqyzdfx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtmmwjsavk.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gtwcxpjbyw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtzoeuwato.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtwmjehnii.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtqifqhole.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gthdnxbpdi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdjqawus.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gtmihnczug.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtzsblzufy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zdqjudy.top/Article/details/gtletifzby.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gtulhaaqya.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtwnmjxmjk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrkyihfq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtborgqsag.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtdgeedkns.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtzxmsnnlw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyfwmespo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtgevkwmta.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtqdxoodkb.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtmeiilftf.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtzrgwelvx.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtobwngytq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gthgpodshk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtoahwlzgx.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtlocfdgie.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gtrgbrpumi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtevmelcbh.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gttrbnftji.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtkcyvezsn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgxtjbal.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gteqerttrk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtwwpqesqw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtofhvsdxe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpacevven.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtngnqqxor.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtrfntljlk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtosqtoumx.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gturzngfnx.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gtbdqxblgr.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtcboukavt.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtslzvgutf.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtpckbtjox.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtulyyrkfk.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtdrdsogjw.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtwtuumrpw.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtobtgqsiy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtydpzsgmj.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtmmerhniq.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtttfdzboe.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gthxcublob.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtxrjcavpt.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtnogaqbdz.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtdmqcggez.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtracqpdnk.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtmubexsbq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoydrimza.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtvnbvgkjm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjuguqlrg.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtqtnytozj.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gtgsqdflqx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtvdcyedzo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtixdzhqxl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtnpfhntmc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gttwaiwgdg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtkyrxvegq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtgsnuuqoc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtaxznqnrp.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtvduttogk.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gttisxlasd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtssxbuwwf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtwwxitbfy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtjwxmxwka.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtaiylxpdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtkiywjxxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gtsobxqryc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtucggcvoh.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtwjdrsjpy.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtlmqvqnff.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtvrrmsglt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtzpwsyaak.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtejkggzcb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gttyzqhehn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gthmaofqwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtwqvjkigh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtsavflvid.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrxwjnmqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtitniuvgy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtcxyhrxod.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtiradkozv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gtkzibtcwm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtwhkijqlm.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtwtiplwec.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtzhylfkcw.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtsgfovoyi.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtzxswbaaw.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtphcbufqb.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtwigzxpxq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtqrxctuox.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gttgovopyg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtgswnylii.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtefejayhe.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtsifryphm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtbxsiujxo.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtxzqsfrwo.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtrdvjskob.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtxfijtrbd.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtaylztelo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtqmlvkogk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gtpbeegcka.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtiqiohvzk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gtqqokoupq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtstelskvz.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtmryinrwk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtijbsbiys.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtpkenqkct.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gthzhxqvtp.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtebqjcrni.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtwvhiiech.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtyolwijmg.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtoopcasao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gttrjedizs.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtserupfyo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtkmvwdbza.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gthesmnrnq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtdatxzrfq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtjibixliy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtkcgzwccq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtjplijvsy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtxalmgqhw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtbliybfwu.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtaxwwkcik.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtbxhhcywj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtmambwttr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtbsohyrqs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtrrorivbt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtvkwikwyr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtzttlwukt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtwfyfxvab.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtnvvwnrgw.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtssoxgfkg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtzzqstugg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtozgjhmju.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gtldtxqlez.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtuisvovpb.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtsfbtnuxn.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gteugwigtu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtpknohikw.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtwlftfxlo.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppfdfbxn.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtrsslykpu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gtmawmelie.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtnmhgzjfh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtundwyqrk.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtitgvaejy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtnfqzkbnx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gtggbxymhw.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtzqpkgeyp.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtwqafgoen.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtmwihwlah.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtuqamdlgd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtgrycswnh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtfcybkxrd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gteunjwksk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtyhlrgbhv.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gthgjnluwv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgdglbw.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtwrdgwuzn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtmkspwgxw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbovdjsvs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtsowhnekg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gteazrzrwr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtytycxtur.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtynudousj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtjzgbbmyw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtauswlukc.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtojadkedn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtdvpechfp.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtfimfbkdc.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtcmcmhbyn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtclxkehqw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtbmksmkyh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtplvqkpyv.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtbbvbwfik.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbovbdyb.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gttxnkgtby.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtguifaeny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtmekppfwe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtwpwlhmst.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtwhdppzrw.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gttohbarou.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtpftczjym.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtynnkvehy.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtdmsmcexe.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtylnmlaat.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtljxbfbbk.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtwrfzozsc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtqzydsevr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtyxwimkje.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtpfdhvtww.html


<!-- 参考信息 -->