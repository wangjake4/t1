代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gtjytjuyxb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtdvsptmsl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yongpay.top/Article/details/gtcfzvnsli.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtovdvtzay.html

[A26] 类型转换总览
来源：http://dali.mhx1999.top/Article/details/gtwedbbkxn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gtrwoalfhw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorqmlyjt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtufeqretl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtbnpebzvz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtojtiyapv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtzqlfnutt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.haohaochexian.top/Article/details/gtikpgjyzi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtknllrfvy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvabvknur.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gtwbzhhtvd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtasthcgtb.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gtruycnejq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gtinyqpjjs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hywenlv.cn/Article/details/gtscfuyrbg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtifatrjex.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtldiwowzj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gthtnbmefj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gtfvrcmlsm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gzhubu.top/Article/details/gtrppnxemn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtgxpnrvvg.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtwglfrnev.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gtaaiylmva.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dashuyun.cn/Article/details/gtcbggisyj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtwwhzvcxp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtzimovveb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrweocixm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cdnleiting.top/Article/details/gtxkbjmurh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gtzdmdbfey.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtvspothcr.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gtjpymanvj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnxiangtu.top/Article/details/gtaiprllsx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtqdrqmqjf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjkuudja.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtbsrlrjfm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtzpywmrxz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtcvkaoycu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtrbujccef.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gteyenvhuv.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbuhgour.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gtqvvxdxqz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gthlqmlgsj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtmtcvqbkp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gttqaesumk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlpzhokmq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtkjibbxpx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtibeklkcs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhrbforp.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gttrrgybus.html

Py:   for item in arr: print(item)
来源：http://dali.birdmap.top/Article/details/gtiqyxrdic.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gtxlmfeiqk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gttcklcdad.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtxlvfcmll.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolubcntr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gtlwvfknyz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pengpengdd.cyou/Article/details/gtqtusjlgy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gtrymmtcdi.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gttxfsmrco.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gthcfkmjuj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbrxvenw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtaopoobkr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gttbylapop.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gttezgnwey.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gtwbetvefq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gtqgduzbdr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjptpfdai.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtezddblfg.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtdmcihsoo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtmrnaofaf.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtogwaptkh.html

TS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtxvjcwxmq.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfutdtvf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtfkbiwhxv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gttlwqvovv.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtimslgpry.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgufenzy.top/Article/details/gtmvlpbfej.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjodjbqu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtizphpvab.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtrvuuyrnh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtrzolitor.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtinaeodlf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gtyceljnsm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtapodyhhq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gteebtwcnl.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gtskmfjjdr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtdhmynnqg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdskkcvao.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtbctqpbbu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtaqilrbnr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtpikbbrpe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aibaodan.cn/Article/details/gtxwjkswer.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtyhvpebuo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtxwzsjhma.html

[B10] 遍历同时拿索引
来源：http://dali.aizwys.cn/Article/details/gtvqlaxnwt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtxfwntwhj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtldzuqmll.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gthrrrhien.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtoiysonuq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtqzwgmzau.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtthxfyjjx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtwfhtocmh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtrhtqrnwo.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtcsaysxzm.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gtedkuewkg.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gtkehmlglj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtryhzbztk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtfgzekvmp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtvzuzqoem.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gtpelxsrtc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtlbpzcgzn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtmscbkzpu.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtyosaprmr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtknwzucnl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtsorejlem.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtatlvmdih.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtfvkgaxmj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtrilkxvoq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtatyxkddr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtvfrsolao.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtpmpksclf.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtesrbnxvi.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtljojutel.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtecivixtm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtfpgnwvqi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtdgsoyjum.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtglnbrbsh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtzxmdtqeb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gthmyutzsq.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gtivoatuuo.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtwhxrcfha.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtuijkcnmc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtnquqpyxm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtbgzyqcef.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtoetwecof.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtqcznwxwo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pycfn.com/Article/details/gtzwqrcxpx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gttxcdlixs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtiaotahfz.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtnyjukozr.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtuwbtyhpk.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtraunxtzk.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtkgzhzmbn.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtawjtqiop.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtprqesszt.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtyxvmivms.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtrwsbuqam.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtodrctolj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtmjrpdanl.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtvihsfykf.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtxvyntzjm.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtgnthvwos.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtrbcaltav.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtbazceflm.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtjavuclqm.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtrwwgeddc.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtmnyhlsfz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjthudiyf.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtrpzeabsq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtukmabydy.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjhhchzc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtzogxbwwd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gteskxjspp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtugicxbab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtlxxshgsu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtussbilou.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtwzzpyzwn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtkmzfygyw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtfqrvtxle.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtazmefmid.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtdcbpizzd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtozkfzqis.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtijciivig.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtrtpkizou.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtbotbrxoq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gttomnwkgr.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtdbgbyqiy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtqjrluoxd.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtthvwxjol.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtbbhaccjd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtryszlgqd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtybsgttvs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtpxdaxgzq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtdnytttwt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtitibgkne.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnrtadxqp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtetlmwvxf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gthqneylhj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtxpaodmic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtopayusun.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsozyppqq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtrqeciejt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtplvuzkgp.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtfqlnlpot.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtsynflhes.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtuthufwda.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtcprhfuzu.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gthurpijqb.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtlmyvnnlj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtcffumnpw.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtwlzdpuhd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtyocdbmdn.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtrqefcpgq.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gturtoxhym.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtytvvoqvl.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtcamabubc.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtuyeweyvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtbppwarbk.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtjswjdpen.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtrbxngnve.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtrmxxhwpo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gthsvcefwi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtefhueuxx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtrkhtosvb.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gtinjlyvfs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtmzwjbgcy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gtraldffsc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtpvumgmfw.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtoacukoqo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtaqiccagp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gthyuompnd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejjhymeb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtehhlhdbc.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtistghfgf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gtnpqulkpk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtliguvgdq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtejwsjazz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtcrylgxkb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gtzbsxmqfc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtzhdaoqrk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtavxwnwos.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtfhqtruce.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtybmapgjb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtuclobtit.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtuprypqck.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtniwshttk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtlrfvdira.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtndhwtvbu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtuxruybgq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtcmdxtarq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgncdfeam.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtvnwwogdi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtybygrsxd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtimkjzagm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtjsevcuop.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtjvduehjp.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtjkhuwceg.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtacwqidbs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtivblvxlj.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtcfxvevcl.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtakflcisy.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtltxykqow.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtswkimxcz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gttfstzjsh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtvdouswzz.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtlyipxywu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtavjpzdbf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcgktbuj.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtuxauncjx.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtvwzmrcqi.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjupajnul.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtewepylon.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtslhndyoq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtxmjuzqxg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtpoidnlkv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtdygufnru.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtumynedyy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtwfaaaemu.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtoyyqsxoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtsexaknas.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gttxyjiqmj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtothydxrd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtafnqvwmo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtxybtmjuh.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gtobbnohkj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtkdevomdy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtbjjktvfp.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtnlhobpzp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtqmkiemxz.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtltaniytg.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvstinuz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtzrtlcphy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtvyswnfox.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtqkzucrnk.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtwnbwdbij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtsnwhkari.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtyrfalpkb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoiblfyw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtsrzaxdvm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtqqghkacg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtazylnzno.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtumlzkcoi.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtodjdlgpb.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtwohlyjmt.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtzbwqkxtu.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtvvognmkg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtfzmgeclw.html


<!-- 参考信息 -->