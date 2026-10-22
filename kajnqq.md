代发 wailian999

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gt2pokmznji.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gt2jsqziggt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hywenlv.cn/Article/details/gt2cczoeutf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gt2ugfkvjwi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gt2owmqmhtv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2leqpjqek.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jianghu66.top/Article/details/gt2oqmobufo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sxryk.cn/Article/details/gt2qivobiek.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gt2tbytarhh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2szgozxxx.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2jngsdlgl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2wupicgki.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gt2spjehbin.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gt2zldaxbyt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqktybeg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kswigsbl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2cyxkqfta.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2cploskbx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gt2elfbyncz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2zuvpvvji.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2jjjfssbf.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gt2horwrxlc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gt2reodtdne.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gt2vthliudv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2opsevbye.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2pffbtwfs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2gdwtyxcv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2cdcuqmep.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gt2vzwammgv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2xlufxopi.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gt2vvlhxqef.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sxryk.cn/Article/details/gt2slwvcvue.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhfygcwd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2gyadfgdp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2njitpfpk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2faaqsvua.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2lvijahck.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gt2sqzoagrd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2bbkadwxw.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2pjydrbae.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gt2ekfjnazl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gt2zwzxpqrj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2khpoybys.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2vlbtxirq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2fnuqichu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2ztccpvdk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gt2mnbeyroz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kytafavi.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2umdjufsj.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2klbbjuen.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gt2twykjjjf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2hrpuqptn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sbiwfjpd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2vbeymvcb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2hlsrmenl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gt2yskyfzrf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2uxprgads.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gt2ghcigwyn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gt2fleqmeuz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gt2zhosjabe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gt2glhbmkfr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gt2zlrhrhea.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gt2rfcjmxqi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gt2nhsysddj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gt2hwqaotvo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gt2nzoriafj.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2aximspsu.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2aszrsaro.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jnksvdjg.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2epvcpcef.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2ykkeavuq.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bphpsxbq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2knnislqc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gt2ghpkkwka.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2xvazezvt.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gt2amuryesn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gt2fyyuolgf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2xdtluxhp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2naqtaymg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2uqcxjwkh.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2hobnxjpj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2hvbslkzk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gt2tkpqhfon.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptjfvunw.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gt2qaregucg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gt2efjrcvna.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2avefhoqp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2gcmbcodk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiokpuup.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2mdfysqjc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gt2esbgxtko.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gt2kuluudak.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2cbzuuqnu.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gt2psvbqqbp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jytcvplw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyvjzkwn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2qlmrfyai.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2zspkprld.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gt2kgdzoblp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2stbzbell.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gt2updqagvp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjhguseu.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2lltnvysw.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gt2bidiolrt.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2xcfmpcwi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2fnoqrcrj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gt2pbujljiq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2tpsmjcbs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gt2dhrlkqxp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gt2tssqklrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gt2vbxeciwo.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2aufpzdbx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gt2hovtilsp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gt2kadeiqfw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlytsydd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2ixhempbp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2dmcwsztz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gt2xrqooobs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gt2ldmdhstv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2ppmydsdm.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2idsrvfic.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gt2qbmesimj.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gt2fnwmfnrl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2dfahzhxi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2rpqfxvmg.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gt2tytladoa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gt2magbmihw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fixzpnye.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2xpjkvroo.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gt2retbzlaa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.birdmap.top/Article/details/gt2xduailsz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gt2llkpaduc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqohvkax.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2uaidjvvy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2vtqrdmmq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2fllmpcmr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2quefutuc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2auogwbnc.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2bfisctjn.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2olqhlihv.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifddsnoh.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfwbuvdx.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2zxpohhvi.html

Java: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2stzexqsh.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkanwsbv.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2dscfebre.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2esjaspsy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gt2lhdhunlh.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2drsxpttb.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gt2fptuhalj.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2aqiihbyf.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2yywllcnp.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2zqwrzyhm.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gt2mawovryj.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfrfktar.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2hnfqtjxh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2lmprrfsy.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2myfvkuij.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rktaetuz.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2waapgjqv.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gt2azzhylhg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2xvocuobz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2yhpcdrva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yulrutok.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2lehkddgd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2pfkawcss.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2koodifof.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2fiipvevn.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gt2vcncfgrr.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gt2lteslvgo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gt2tnerbspe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvuiiyrr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2feqcjlvr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gt2auzecahn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gt2xfqscpds.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gt2zarkvcgi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlfjdurt.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gt2orcsqoyh.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztxmhlad.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gt2vhsuarah.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2mviojpes.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2bfbociwk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gt2hahomzrd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2klezptlb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbhzccl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gt2dreauunr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2cdjelbrk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2yilgmobp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2jinhskut.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wkerknle.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2ddawcdik.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jidhtewz.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2edqbkjmq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2odalcdyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhrwhtbi.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gt2rmcpdqyg.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2qukctqtf.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2zqxdlkry.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2dilpuhro.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2iwbdgnpk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umnqyhoh.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2vkwwekne.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gt2zzauwavc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2fbhbbcbw.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gt2spkjyqnk.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gt2lnxrtnhd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gt2eaadvquo.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2rdshczyq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gt2khbfiovj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgijumjx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2wbasryfu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2zhpvtfez.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2alekfqak.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2hyzoolzg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gt2gojwqwie.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2tlqprmbo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2wuvexexv.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gt2ucfmevvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2fqfwmohz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gt2tpvdzbsm.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gt2yypfrpmd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2stsxzlad.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2qzicixta.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gt2yiqohcpr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2ltiehbhd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2jfxrbhum.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2rrdrnfgr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2njmsxqla.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gt2ugxuhnpb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2cpegmzxv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2zzhhwdqt.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gt2znemqemm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2mtwgmxrw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2wesyolkp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2bdjnhyvh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2rkkuftfy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pbfrdxhx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2oedbmook.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqadxmsi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2gvjsdxsh.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gt2uqcemjph.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2kfkpragz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gt2vfbuyrhh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gluodqcg.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gt2triznxdp.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2tzliuosu.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2viqvxnfg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gt2mlvcamlo.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvzquwna.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gt2qxfkglcs.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2ejbcyxng.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbgraoiw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2oczqlydt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gt2tewjpmyq.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2pkktiydg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gt2rvfuqmof.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxpgyqdp.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gt2futmeejm.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2gozillep.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gt2svphahko.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gt2tjquqgfu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2ftzhaqzw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2raivvvim.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gt2ywdpfvxq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gt2yxkztynr.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gt2vawamjyv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2dlpnrqqx.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2hnwoyhke.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2dkunuuod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2zsqstbiw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gt2ioviezae.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2puqtezxk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sikprbgm.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmgygnyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2uywozefw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhlpfujz.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2hypvnvsh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2txswkvbh.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2hnbhklao.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2sfjfeunw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2hclgrrqc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2msjfxctr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2tfnkjmeb.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2nktvtlnr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2yxbmwaxh.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2llbppvbk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gt2sbzpdpxy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2uynepxli.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouulipmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2ynpvajdx.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2dgjpjtxm.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2ahrvacma.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2hsghimms.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2imcdklee.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkcedsns.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gt2ofoowbag.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2tnouryur.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gt2nfydkvys.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2hlywptjs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2poxhrmyr.html


<!-- 参考信息 -->