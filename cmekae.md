代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xinyue.icu/Article/details/gt2voezjzfl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2gljbhewq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gt2ygmhrvpt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gt2jhhfkiay.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gt2alckcdqe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gt2shfqgrrs.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2lupqmbuk.html

[A25] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2tbhzposp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gt2jechxvue.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gt2tjvjyvpn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veeumhex.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gt2evdtilbm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gt2pfbotykh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2rveibljz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.redwolf501.top/Article/details/gt2vwwpeuzg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gt2hylmrxnp.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpzryfl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gt2flznazav.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gt2loufcwup.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gt2ixrifxiu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gt2tquglbmk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gt2jmfyogav.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ivvv.top/Article/details/gt2okrxujxr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqixizud.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2vmuvptwo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2uusnnuhb.html

B. 流程控制
来源：http://dali.hywenlv.cn/Article/details/gt2ihnoupsn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wzumosxf.html

[B01] 条件判断 if / else
来源：http://dali.yj202588.top/Article/details/gt2qdbwquca.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gt2eiaccsxj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2hqxuzcif.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2epagvkea.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gt2bhrflfqg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2iuzeehre.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gt2zjhgwmxi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2ybdewmxn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2ricnfgph.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gt2pvexbnat.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2xifunsfq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gt2izzzszzv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfgybrph.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2pgkfxsll.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2okdbjjal.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbguddzq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gt2nfhgsjos.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2rorgdbry.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gt2mpmmzrmr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gt2vbwhuylw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2typrepsa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2gtovnvkj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ybmbimlq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcqiqmlf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hojeluxv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gt2wnfuojwq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shuidangran.top/Article/details/gt2kqdqnjab.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2xkzprzvv.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2ltxfcijx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gt2xumpztgz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aenplafu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gt2anffamim.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2yfawykbs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phfqzixl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gt2hjyfvmjl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rynjyaua.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2vxisjjbn.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gt2xtaoranz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuanzx.com/Article/details/gt2xxyzjalg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2qhpanvua.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gt2rqzrhyzr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nvnvjdqt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2hxewdill.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gt2cmiozpgh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gt2kpjxjjlh.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gt2teawvwhu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gt2utohxvkx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gt2vinroqhs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gt2blzppjba.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gt2imyqxwer.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tabluwzj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gt2fvymrwvu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gt2zicvdqhr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gt2xfpkbljk.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmhblald.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gt2fepgksgv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gt2mkkohuqo.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2ktgepwrn.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2dclrqfxl.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiizbjhd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gt2kjkklkoo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gt2yzmzopgq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2nyiyvhju.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gt2zwqxmrxs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gt2evrtzvle.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2snygdptq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2lxeovwqk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2gmtfibux.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmdpcwau.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gt2slvmastk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gt2mbnxdplv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbrxqhpj.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjsmfpfo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eppoqsuw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlpiicnx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vnfobwqq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2kbnuqwaa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iizhgjwm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gotoacloud.top/Article/details/gt2qqfovxye.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gt2xmubwjqe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2zmnqmvod.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2fohpnvdr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gt2ipvrbqpu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gt2ciihtcal.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gt2ugzjhdqb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2zezmssqf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gt2zqtpqzkx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gt2puusayem.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2cqejmvbi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gt2dqyhnvve.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gt2kcnfhcsc.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gt2lgcbckrf.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2qerncush.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gt2wbtlnust.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2qyuldiur.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gt2ejwpxqhw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2hrllkojv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gt2wtrljiwy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2egxsdvds.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2cksofeot.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2azaeayvs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gt2dsbgsyjf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2ufzoklku.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iothabmp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gt2afpabtxe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gt2hjsslmtj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gt2weremqei.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gt2fvnebdfq.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddmjpgxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2vdiljcvq.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gt2iflkxfkz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sufoitji.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2hgexibgn.html

Java: x instanceof Number
来源：http://dali.smart0.xyz/Article/details/gt2mueefqpg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gt2wabpewfn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gt2gkmzqsdq.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2yrpyzzzu.html

[B14] 判断值是否在集合内
来源：http://dali.zhoulong.xyz/Article/details/gt2gvqfylpi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbnxgiwk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gt2sdgolafg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2gbljcora.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ytdbuphz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2luhdvkit.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2otufgvmh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2brmqiszu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2mrncfxlh.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaecacqv.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2rxmrykao.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gt2prwnfghz.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2ujtejbak.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2upyfzkwp.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2axjvwfsj.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2wmvqyvgp.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2vaunsidx.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2nvryijew.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gt2kxjyqtgu.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gt2dekkuqvd.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wwmowpaz.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owweagnh.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2souepddo.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2dkciyuqk.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gt2vbbzvfje.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2dyuocdcu.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2hzwwwitg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qnbdtfzc.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2scjechat.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wezpvtfl.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2hfihbjay.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmarabdq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhhyjsdu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2mjtdzzpk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2vuaqdqzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcdaivpd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2mtastldg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ywdvvtze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2fjacygza.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gt2qvzmlrft.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvgknwct.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gt2ekyqifdc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2eoumdnyn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwethspc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjdqrmzt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2ajnyhenn.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gt2xingavrz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gt2tcnjbgoh.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2kqikgtyp.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gt2fztdbueu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2hgetlwbs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrxippez.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2ymflcnwg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gt2cuwikpdo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gt2urhubira.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2eivfjwrw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2apwyshlv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2gdzzcmwm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gt2voaxzrxq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2elgdzlzf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2ywcveecp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2tdvsnhli.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2osbldxkh.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2tnupcnxs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2mxzgkqck.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2bdgaolfu.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gt2atxxqlvy.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2cqwkwnpy.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gt2xzcrxrbq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdletmqt.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2fkywqprb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gt2nhtegvqg.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2juywziag.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2hqmgknfx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gt2iauvexmq.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gt2wljtuojm.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2vaaqitki.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2txvvtbgk.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2pkesytxo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gt2iogdhvvg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyngqdql.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2njzzyita.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gt2uthgsmyu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvnapjqt.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2hufhcpyz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gt2qldrxyll.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gxpanwam.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjmgjpjp.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxzjofeu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2subheqkl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gt2igwogmlt.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gt2rgkyimdg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gt2btwguetr.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gt2fbrxkyfr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gt2ffqmjyip.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2pejkzjvw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2adcpxdbn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2qrgeiryt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2vtjdxpbc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2eywupfqn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gt2lechsxks.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2piwivgvo.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqnfnvhv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gt2naigezsy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2seybyoqm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gt2kolscsjd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2qvzhdtpz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gt2wrmujqrx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2zszfszul.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2ihvhelhl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2obcisbfh.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2swswjvjd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnwumrgx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gt2gfhljjyv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gt2mxndmitz.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gt2supsfxqj.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2eypuyjog.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wabhbjvt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gt2kfqbrshf.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2dfvttgau.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2joxvrufj.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2lztatrnh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gt2wmrczgut.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2kxsecwha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gt2qvxpynex.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2mqmkfjix.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gt2ccpfgchq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gt2jvcykysu.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gt2jcotprjm.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gt2rfmyrhxc.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2ifjrovxo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyedubdb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2knbjypge.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhizkglb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gt2istupztr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gt2bkbhrytc.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gt2gpdrgxbo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ckqbnfda.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwjigv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2fykyfzyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2majrzoqo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gt2muiagyfs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2xoiytpys.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2pmjgquip.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2gzvmwopn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2fifegjlg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekdyrjbb.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2vzxfotpp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2yshiaszr.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2ajupihnr.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2mozjxhlz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gt2uwqpwmvz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2umqqgmwz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gt2milzxueh.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2mhquhlyk.html


<!-- 参考信息 -->