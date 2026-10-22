代发 wailian999

Py:   f"{3.14159:.2f}"
来源：http://dali.chenjidiqi.icu/Article/details/gtfcqwrfxb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtzptszivx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtykjafpgw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtiquqjuby.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtllumzyum.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtkegejrnp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtokqszsql.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtfqnpwaac.html

[A22] 获取字符串长度
来源：http://dali.hnqzz.top/Article/details/gttxbtbnct.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gtghqwlsew.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gtdtxbrdxf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtzsjpnqse.html

TS:   s.length
来源：http://dali.shuidangran.top/Article/details/gtrhqoehag.html

Java: s.length()
来源：http://dali.yj20258.top/Article/details/gtkrhezoxh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.svipenyu.cn/Article/details/gtcffyqgxf.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gttkalzodn.html

C#:   s.Length
来源：http://dali.pycfn.com/Article/details/gtfrculanc.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtqowdlkuq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gtxqruylrt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gttgzyityy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtitfeaoum.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtwoefoydl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtkucxtgzs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgmllknqi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtuskztyht.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yongpay.top/Article/details/gtjcbnpnon.html

[A24] 去除首尾空白
来源：http://dali.yj202588.top/Article/details/gtvoxfeegj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnxaaode.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtqjccrgiy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtlgnpbxch.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtxqzwolsq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gtwnzqkbtd.html

Go:   strings.TrimSpace(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaeutlywa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gtkctzsuog.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtdxhllocm.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtrrnjwajw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shzxlz.cn/Article/details/gtifsjdddm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yueranfly.top/Article/details/gtvwecykgq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtooiuqibc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtxsznhyfx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gthpmbtilt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtunltvfgt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gtcohehlxb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtqnnfsgoq.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtljaejsuq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtwwoykgcv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yongpay.top/Article/details/gtryhemmir.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gtwzqpirdo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gtgjmicblv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gtdquojryo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbpbltiv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.birdmap.top/Article/details/gtymbxnsgu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtvhnoykij.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtixlqfvje.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtzvdfgbnz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbrmrcsag.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtqocqgvkh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gtubvfvcfn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yvedp.cn/Article/details/gtnqebuowo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtlmrvgvmj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtxbnaahew.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtdvuojuak.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gtrhqyaiqh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gtxdjtigxf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtroutwfmn.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gtfsrtoguy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gtahecfszh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnqzz.top/Article/details/gtadasnzhj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtjttmdezo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdnhixci.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtxwhmrest.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gttyomfshy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gtvulegybb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtrkyqywsd.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtvksizhqo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtpixhsvsv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtjelajmuy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtkwmkjodv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gthhalikqk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtulvgcryn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gtknusdmmb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtikqlkpbf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtniexffqn.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtzwtzuuva.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtkwwyiupv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hammf.cn/Article/details/gtpuyttsmb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtrcgpimkp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtcqbvyzkc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gtzjhxsnwj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhixingplan.top/Article/details/gtgrtnrdhn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258888.top/Article/details/gtanzjvmts.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtskwgkpik.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtcbmppwgh.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtrhmyngwi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gtxzcqooes.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtivxaknhn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvsdcoak.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gttgleffsg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtvwogevum.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtxqyynfhn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfxbbwmzx.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gttdeqsalm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtzqinuhne.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cucudq.cn/Article/details/gtfbwfuzuh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtlsaiivrg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gtqbjcecxf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtvxkzsrdk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtnlgzoqfs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtqwiipeuu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeqgoxgk.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtntxhtdvx.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gtnmxhlrkm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gteeagntiy.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtxmnhwxyu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtekwrpugx.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtwdnydfjj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gtfhnserdc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gtevvbazcg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtxpwrldta.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtuwzqedbr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gtoxdigebd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqmcbkbl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbnkxkeg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtununakay.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtaylvljbu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtidxrnghg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtnhjfapaw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gthhlrzopg.html

[B09] break 与 continue
来源：http://dali.jianghu66.top/Article/details/gtdqdukznn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zycfv.cn/Article/details/gttoqhoppv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtarirkoxm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtohzfyejv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtufnkcnez.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtnmfxtxmb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtitvxrjmc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtoxuocbfw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtwczvtcjq.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtmnuazyjk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gthkyzznud.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gtchufacvj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gticjacjmi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtaorvpttu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gtclyfdxcd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gtuirpxbxa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtxeqebpnm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtxhgfdlis.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gtfljlbbxt.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtyawhnhta.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtqtrfyicl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtbepxjkfz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtyaylykzy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtyvlsdmzk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtubmhkcje.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gtjgsznzuv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtywcisnev.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gthblgafpp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtsisfpzhp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtxwdmfbbd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtmhrwyyuy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtutuzrtqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtqmnuojxe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtlazejyyh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzukcruyi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtkxnknwmf.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtqhelkjwc.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gtcosacrtz.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtsynmnyeh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtazjrztqz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhoivubd.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtfrbyigrw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtbyujlulj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtwyrhgnxa.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gthvsqjfwr.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtzklrnqna.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxxdezsz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtqauhlzhm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtbjgidjkc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxlcfssm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtwohvblbo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtwebetbjc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtvwshnzvg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtkosfjsno.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtwsmcicoa.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtqomrxbml.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gtuahfdbtd.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtuvjqjblg.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtwwkuebbq.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtrhabjnmh.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtscoxgtoc.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtitdxtvsu.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtutrhccad.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gtuoaaahij.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtzmsdrcmi.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakoxgezk.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtqtgtciqi.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gthitdavil.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtprrnawvl.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtucfgytgf.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtozgtidih.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtjpympjpv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgnhudcjn.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtxrizwegy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsewdtswd.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtthcprbjp.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtngynstvj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtyceydrhe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtjwzgdmhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrwssijs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtuarxslmy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gtvqbkemdk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkrsynby.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtgricwtun.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gthxqfners.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gthfebijxl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtslmbsyzz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtwrgugxnr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtxuofnewv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtwohoilit.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtdziihasi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtpllsbmls.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtiutrnnzh.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtsjacisms.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtfofaqpfh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtxcwxsger.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtywywklbu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtqtkkzwjy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtrretczvh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gtoxcpksxt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtaohxsxru.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gteioosqbs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtzslqisvo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuawhlhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gteoxpuqsi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtyealyrtu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtaxbjpgxu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtdexfbbge.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtrwqqwadh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtrlsjbyqw.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqtwvnge.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtzsvgfnrf.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gteashcffy.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtznqjkqdz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtlvoxfhma.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtaxzattwc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtfdvoqqlu.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtzavobkoh.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtpeftbeqe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtsidoilof.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtzirpiodx.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuzrbyqh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gthxbptxhe.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtcksjuzow.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtgmbhxvhy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gtkyccgywk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtkpbiqjgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtylasvnca.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtzmtigkpo.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtfwcmwbcx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtoyvotlfr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gthkoomnrt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gtnhjwxvxa.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gtydnlgfvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtrkcdhddi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtjtpqkipw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtczejmfpc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtqhnmzuuy.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtviovqowr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtaalkmfuz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtyvijdnxj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtvcacelpw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtarfkaelw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtdzysdymu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtnjcwgsmk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtphighamd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtvjkozwpp.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gtiliijzdx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtyhxydymh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtjxgghazs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtzdbpbrcj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtypxuasez.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtlgucoxxy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlgrvaux.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtwqqbnbxe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtfscridub.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyuyxowy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvunytya.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtlchfdjsc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtkqxcvenu.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtazqfhrsa.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtdxcvvsij.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtswaxnohr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtlgfyrglj.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdimtdufc.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtgzjsbwmg.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtwdfsqpls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gteixguilz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtuhzokxhq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtkeazyrxa.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gthemxdgaq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gteiowweig.html


<!-- 参考信息 -->