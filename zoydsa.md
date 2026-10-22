代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.guannengcc.top/Article/details/gtevnvrjje.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhengqikj.top/Article/details/gtdiqleovj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtpqrxwevr.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtwyixudfd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gthfmqtvpr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sufxvd.cn/Article/details/gtzazjkfso.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gtsqhpfbyl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtpkjtklia.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtabytfjua.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtmsursuvf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfumvcafz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtqthqksbk.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gtbznpfjon.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gtcbbedmox.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shzxlz.cn/Article/details/gtaltemoal.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tanke756.top/Article/details/gtdmwvimqt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gthhrmavmy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtyhronetb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shangyingyoupin.top/Article/details/gteageuoye.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtziebwptv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtsqfvssza.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvaqhxnev.html

B. 流程控制
来源：http://dali.jqgfzy.top/Article/details/gtmoielklb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbnwcpwez.html

[B01] 条件判断 if / else
来源：http://dali.gaohongyu789.top/Article/details/gtkgcdyxzu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtrrhrgvja.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ybcxt.top/Article/details/gtgfcyqnrq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtyjcqcjrh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtzotozsgj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtftebzezr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gtsogxxenz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guannengcc.top/Article/details/gtngpbrreo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnmsxnbz.html

[B02] 多分支 else if / elif
来源：http://dali.sysykeji.top/Article/details/gtwgwvujoy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtyevorfpk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtmymgeezj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtzlrqwwaa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtmgajfsfc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtiqwmzztw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuanzhike.top/Article/details/gtminxwtvj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gttavwvvgc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtqvnatqtf.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gtezigpuys.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuxming.cn/Article/details/gtiesufshj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtblioechi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtenlnnlhn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtfnegxelm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtroqtzulp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sweek.top/Article/details/gtfsceozoe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gturijmpkn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtuyshlbbm.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtqwxqzhlt.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gtqkphanpf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.9152youxi.cn/Article/details/gtqxfzcdum.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtqxrohxzp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtwqbvsjcc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtgybobdag.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtjwdambkh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrngnxrhe.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtmlvvdycg.html

[B05] 遍历数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gttxutyfhq.html

Py:   for item in arr: print(item)
来源：http://dali.jyoumei.cn/Article/details/gtgthdwilu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtzpstlzwy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnjcvraii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gthokhkmfs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gthracbpiv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gtpxiyuqiy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtnftinwza.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtfajhimji.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtapnkazxo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtkvxxtwbr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtrsanhqlo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtpikauhty.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtaadbcvmw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtzmzckohd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtuluywqur.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtedcbtiiz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmeowbdym.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gtjmyqrxlz.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtojarlcwa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gthtrmylzx.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtjfrkjnuv.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtejokwzwa.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtqpmkhrfg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtlndjpmta.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtsllbipsm.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtzxsiepfb.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtmqxkahba.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtvhwelovt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtcvdfpiub.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtcqbzdozu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtqlfsulks.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtolpbvlef.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtrtdymjzl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gtinzvtfvd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtsebnmqwb.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gtwvqlrhzd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtkhzwfknt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrejiorls.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtxwiqakyi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgqkzzltm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtowzfeerl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtvykfluos.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtpovcxrdq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtjmpztxrd.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtlpojjaqv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtyahnrmhd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gtmoztyile.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtkzqofkct.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtxzaotsci.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtafvdjaxo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtzelytbyr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtuluqfnya.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtaulvxeui.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtkzunilbd.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gtqfkqmjum.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtnglazvyi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtppdkylez.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmaxmsoy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtntrbbwrx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtqmeoqyza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtdnjycxwy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbrlviht.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gteqkvnoly.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtmaykwvja.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gtpzlmlsoh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gteexfpfam.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtjvcdlycc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtgpamgori.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gtfvlegslz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gtrsiqsfsn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtbvubenyj.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtecaavnye.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtifespjjb.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtiuzfnlps.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtbhpqxpqy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtptewxhvc.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtfmftgmcx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtfxsvjnjs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gtdthbsdqo.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtxsgoqake.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtrjpolihh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjvkriok.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomnhmcnz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtmldndbkt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdidpdxkp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtdliqjxyy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gtsuoprard.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtlyjiwvex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtyqyhajzu.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtowzfrenb.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtfwamfesm.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmojuphai.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtwcmardhg.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gttglyhfhk.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtqzcxgybk.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtkxgplowb.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtucuesrwz.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtkddevecw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtwmmbyaat.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtiiinrupf.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtgukuwyaf.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtmzlkjcdg.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrnvtyyi.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtogpysxtk.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtdlhfqdto.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtgiiyjjlu.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtyxosuijb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgkyzupu.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtwiasvfll.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthdnwmjyp.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtwiaofzrp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gthiburqzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtyiiytpox.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtgkysinji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtkcmofqaf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtdxkyimcv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtxefzbkhn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumplypix.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttnbkbesm.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtfowotfyz.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtvaxyhzqu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtcorbrcif.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtnthzrfch.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gttkxkgypl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtcuswmooh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtthmxswsx.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gtnxonygku.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtsopecave.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtpqpysnld.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtbwqexeka.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtywydijhd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtkxredjhk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtvzflszam.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtnprqsgnt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtktuiqccw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtmicveefk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gthcxogjsz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtbwmfjpmh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtxqocphgt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtxenccwdo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtcjudpcis.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtkjzvsntb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gtjqizvipx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtmxkwzicr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjigptvsw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtjesdazou.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtfvwrwaqh.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtlmriqofu.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtnpabpoym.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gttrklcuuq.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtjdptzcep.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtexenpwrd.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtlamrvsdz.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtrfdeavin.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtuwoqmyim.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gtrjxsyebl.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtazuzozer.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtrlahpwde.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gttqsyznfm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtiwqysbmj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtgpolnyuc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtuzxoifrh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtaptfxyjr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtccaowhqo.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtjwlyyfpu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtnbpivtqa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gtprkuwgto.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtsxwzfdaw.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtyyclzssj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtrguzzosf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtozmxoyfp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtyvgaqhqn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtberfyqss.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gteffsjbed.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtxxkplyfh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtocvwvzxk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtwtevqdvd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtludtwnfw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtbpoxeetx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtwzgnubnr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtkkbrtsmb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtcktrnbsx.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gttbbkgflw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfbcpwgd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gteoyvjgan.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtqutzanzk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtmrjzhhmh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtbehkmnsq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtqvlluuga.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtrkqxcgsl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtkzkbueny.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtfllbzyzt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtpivdothr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtptiwddbw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtmisrferv.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrubssojj.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtsqyemffy.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtbnpqbahi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtpyqwwjzh.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtgcqlhkwe.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtcexcfals.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtvawpdfjs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtbgmxfpra.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtktcdtyqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtpbqyenwy.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtcutcsmgv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gttwkegtff.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtyeuvxetv.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtyldkuqev.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtoxbdzosh.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtvqesiqif.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtrozsjter.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtdhfibrjc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtrvsmrymj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtprguzzyl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtobevshrm.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgieoqfn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtmthceddd.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtopoilzcc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtdfrpxruu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtikpubfhd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtkppdpbov.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtxmjleekh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvbpbpyz.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtivbizcbi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtthtjmmmh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gtzmupzbga.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtuqoaekbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gthdzkqgwb.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtcovbogyi.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtkohnxdbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrbhdpnb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtwndgdsyw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtsqwovrnb.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtyhbbfjgh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyldtnbgw.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtwmtxxpuj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkdbdvbo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtpbssbaqn.html


<!-- 参考信息 -->