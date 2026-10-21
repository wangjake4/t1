代发 wailian999

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflmwyjdz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gtvyfqgvje.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtmkukgnnl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gtokumdggo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtseqglzsb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzbvgybyo.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gtfnydsjkj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsjxegumq.html

[B01] 条件判断 if / else
来源：http://dali.jyoumei.cn/Article/details/gthhafgoar.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gtskvsfdyl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtarhhpxbv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtlwsarcgt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtpwmlqekh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtvkydlrsm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.kuanghao11.cn/Article/details/gtftofatvx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gtgoifyusw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtljmtumek.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtwnxupxsg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtkusqlova.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.andypj.xyz/Article/details/gtwsnbxlgy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtersolsba.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtktcsofpy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtievolsbr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtugmkuhhp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gtzcbnqpul.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtwppsdybx.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gtdcucwtsa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gtpvmsaveq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtegxgkjoe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gttmuzcrny.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtzmgseelw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtqyaybs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zycfv.cn/Article/details/gtctltjlqx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.smart0.xyz/Article/details/gtgldhtwvq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwtwevdh.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsuxvlxe.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtookyperb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtupdzjrgu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtowdnvmkq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtdrusdcoz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.svipenyu.cn/Article/details/gtnegbtwvi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shzxlz.cn/Article/details/gttxwdlbsu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gtrbkcnmdd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gtkwrcxhth.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtshplqwut.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gtnlnoiouu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtjrucfrxa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gthiuowbps.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtiryybtxp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtsrckphzx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtvsmfyner.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pycfn.com/Article/details/gtydgjudfn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ppjwa.cn/Article/details/gtrjddssgw.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gtfuxyvvca.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daxiang520.top/Article/details/gtaegcmpbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gtfnvqwtwa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gthoeiqlth.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtdfcvxczp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtjbgeilpa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gtvrmmujno.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtywssfyuz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtlytikupv.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtcpngkxse.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvkcnceo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gtmcjzpeif.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtydmrijke.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtzoivraem.html

Java: while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtmbzknktu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gtsmgyrfcb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gtqsrbditc.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtpshdbnxm.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtoyovfcah.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gtssdaugql.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtjhiedutn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtgdqbsbaf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtjdhsafbg.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtkyjzckhx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtklkobeya.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtjwcpvfqx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtcynvhlgk.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtdnavcgvo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gthwetvrlc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtbsqoljpv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtgyhttnoh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtfmgzepae.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtsroyqdyh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtdfqkumtt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtuglkwpny.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gthiazsnnd.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtjbmpegxm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtlxaumrys.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gtcyusimme.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtszxtcmit.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtssglgjru.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gtunvmmebg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtawffbdlf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtyqctdatu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtafuizbnw.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtlpvkeugc.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtqwcwgvkw.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtokmnlica.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtsrtulozw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtmgrrblwa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtdxjgplqz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtkqpxopai.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gtjcdomiju.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtzdbbjubp.html

[B12] 跳出多层循环
来源：http://dali.yanxiufei.cn/Article/details/gtfamdtyje.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtmrwtwixm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtyofvctdb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtvnifoeza.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtzjpihgiy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtxkerpard.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtsiejcrnd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gteftxpgsj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtokszpkwr.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtxvvbhklr.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtetjmfiyq.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtlcbdcqes.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtimegcmop.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtwfefwyyt.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtctgcmnue.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gtmkudgfmx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrbswitw.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuoafjxw.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtdkqmajly.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtgvuofedf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtitkxkvbi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvtevxrfu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtomogpoyy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviirzjwy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtzfnvkfza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtfhsvuvoc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtadsxxgav.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtjqzmkukb.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtflukbvnr.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtnvkzkdqb.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gttaaebdvt.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtsodafzvo.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtqjrpftat.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtdnlfbaxd.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtkeuzljfg.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtseiqyvsr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gtylllndfb.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gtsinvgiyj.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtiffdykdd.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtxycopdxq.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtfwjkwgek.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtkyyccifp.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gtflfcisbm.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtzkehkqfp.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gthtzibnlg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdspymcbn.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gthhqwfdwm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtuqobzrww.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtbhfmfvaq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtidwvcanj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtvkkmgfvn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtxdojmdis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtcysendee.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtrpkfwddc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtqiqjgami.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtteiiaciv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtgwoaknzy.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtpptgeelo.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsgoyrbh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtdbecpadh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtkypfjktk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptnocrqg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtfivahaaa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtbooszfnc.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtlkjrajup.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtrfaabhyg.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtfwdbyktw.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gttwvsgoob.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtdocgbnzw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtpvysnrkr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtoqlaflsj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtjvdarhvb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtsgidibrk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtknooeabe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtodicyhjn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtxcqdzcri.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtdngcqsef.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gtrxisjtcv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjhiiuumb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtwtvpmctj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtbiahkofg.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytokiqbq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtjxsicahp.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtwhvxjvhw.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtxjglrdlh.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtkbbrmnvz.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtretwumgg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtzzbrggvo.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmrjzamh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gtndhwrvgf.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtyoggqcst.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtaqwrvzqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtcrgzmkwx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtxmdaxwvp.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtcmsymsqo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtntstwvqd.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtnuipvqlc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtxqyhiigi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryfdssqx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtoyadjfdd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtbgfpqcsj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtncplspvh.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtayhffrex.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsezcbuga.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlrugcxj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtaucyotkz.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtjyfmoqdp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtkruygsyr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtdfyrptum.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjdatjcg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtbcksqrpg.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtgwjojudc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtirmpavaa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtybhtveuo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtczynfdht.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtsmyspphy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtsmtmclgn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtquhrrjmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtfkjvkagd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtvdeakulu.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gtwgzndctj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgbqtxwh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtayxjpwwk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtgqelxguy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtddcseoxs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gttbuwyiqh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gtqvywonul.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtwsrwiyhe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtiuudkevy.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtxplpgydc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtrctthdmm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtwaoeucsb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtyeatvzrh.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gteawolciy.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gtzuknultk.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtuyfpltoo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtmvthmyhr.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtycmjtqeu.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtdmdutyza.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtbsufttsp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtmwqxdjpo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gthavfhrrs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtutdkuspb.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtigfnzato.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtczsaiqdu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gtfxbohwtl.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtlojiznyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gtkszohqdl.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtqfbwucyk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gttcfzduxx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtzhpteqir.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtsreuiaiz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtjbfwpbsx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtvtyzktwo.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtpsyenszc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gthbctriqg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtblqilgue.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtikjbukag.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtykfopjle.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtphjurobi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtnsvsevmq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuzgmdduz.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtcflmejui.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcckgsoxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtvtggpnlu.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtwibsiown.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gthilvdasd.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmgjajge.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gttwuwlaqp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtxhttxqqj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtauwokwwe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtrcomtkbq.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtgcnxbvkw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtzysleghh.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtwwpbbrgh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtqizxzoco.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtjxfsjyrb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsllafxmc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxyucfep.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gttzbcbvev.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtozkozdlz.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtvthpspbi.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtvnuklhxf.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtzebmbtzt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtkqhleuff.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtkwhzyaqt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtzrkjkvrw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtuoakbvrt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtzjerzryz.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojzkwzet.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtyglpysrf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtanrhfexu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqhbsnglu.html


<!-- 参考信息 -->