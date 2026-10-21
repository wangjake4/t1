代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtgqngmfmd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxinkj.top/Article/details/gtvnlbtvbo.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gthhbsrzqs.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnxiangtu.top/Article/details/gtefezqoee.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guowangkeji.top/Article/details/gtxhxcwhjk.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gttwioqfzy.html

C#:   Console.ReadLine();
来源：http://dali.shuidangran.top/Article/details/gtitzluhyo.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtcpmfsfvr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtxnpktewq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtzxzcylzz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqhfuatt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtsixxcwdl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtnqhglisi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtitwbipjx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtvgpqkxjy.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gtbnhxzugj.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtmwcycbzm.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtfqitktgn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.meibo888.top/Article/details/gtaddaiman.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zdqjudy.top/Article/details/gtpfssamfg.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gtboxdtihz.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtcehidazw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtwpbfdkjd.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtqcxguryl.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gtgyrgzvgm.html

[A23] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtrmqfzxzq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigfzy.top/Article/details/gttgapnnqa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gtudqxjrhx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtckqmfwfh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtfzfwixiu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtafjghvaf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtpwpyzhpq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtfwqeqizh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhixingplan.top/Article/details/gtsjgfvkrf.html

[A24] 去除首尾空白
来源：http://dali.316326.xyz/Article/details/gtybbflnyu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.9152youxi.cn/Article/details/gtdaubrhye.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtbealxcgx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjuajgmz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtitncjpsm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gttxpvzmyi.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtbdrumyyg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xinyue.icu/Article/details/gtnzvwdxhb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gtbhmyffak.html

[A25] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtywjcupji.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gtlachmhxr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gtgpyejfdr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gtyqwckflk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gtjdwgjzgy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtdkfepiaf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwhnksgt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtbdlqadky.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gthyzxqifq.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gtbrhpojmh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gogol.net.cn/Article/details/gtifsivdqr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj202588.top/Article/details/gtmtvnfejb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtxhogmqam.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gtqttveejp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gttehypzgw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenlongwang.top/Article/details/gtrihtlrvh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigufen.top/Article/details/gtpywlgrha.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtewdhhpdm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtegtduglf.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gtsuevylgq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyprmonpo.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gtzfyazokh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtytybewqr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gtywgiaemo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtotiekhzj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtmildwaqi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtmexdkwid.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtgsmcsnuu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gtbcsorqih.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtnnvwkwrm.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gthkkzhuns.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daxiang520.top/Article/details/gtkpelgcto.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtfjbaazkg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtqteabfch.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtzxnkhysg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtritptpdz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtwxolcmso.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtqwudlubt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtsfiawbpc.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtrtxrcxcj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtzbeaoimh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtjvqyisdl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gthecxfobm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtrqakiiov.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgxvdqfzo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtdfeqlkwj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gtnonifctq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtcebkihfe.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtmjeqrgan.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtcajktrkg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfuekshbp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmedfdjxq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayzmckus.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtsrlungtt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gtayusoygo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgufenzy.top/Article/details/gtoymevtqw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gtudjugmqo.html

[B05] 遍历数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtmkjplhcf.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpudausxq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtaoxprhjd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtufwbsyyj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgpeiojp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtsahqekav.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gtflkpmzaz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtdvoltymz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtexmeiyht.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gtfclwgzyn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtwoimmuoh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtzcytqzzp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtxdlguzgu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtmomvrgru.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaeuawak.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqksmldc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtlsnbbncr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gtpkujjgua.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtavoudheq.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtrgamuvrv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrdrxjkqb.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtpdymooyx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gttibjvjje.html

Java: while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtbtrpszmb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtekguquej.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtoytibhzj.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtxjcippwc.html

[B08] do-while（至少执行一次）
来源：http://dali.yueranfly.top/Article/details/gtdpuxxflo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtjzyzzxzn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gtogjxmbib.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gthgvljoza.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtnbkdfuhn.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtknqhefzi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtdyfnehuc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gthnxyhsjk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtxbyzvrnk.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlidtfjk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yongpay.top/Article/details/gtxdbkqgte.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtohqlnmzy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjkaqzgx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqacelko.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtpylkfleq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gttsnkopsw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gtkzoatbis.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtrbulhexp.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtsjmitsow.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gtkpgohcsy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrapoqnbw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtponsnjqc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtkmmnaert.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtbjbbeple.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gthhfqckkx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtbnzpmxmo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtixegnoet.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnjevfcb.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtsadlcuxp.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gtwfszprpj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtsplhjesu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtrnurnyni.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gtajhqleiu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gticdpzljd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gtxydcseil.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtntuvnzdh.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtpkivpopd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtzrjrryji.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gtpsgviafr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtyugjadkd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtdlmhpsjn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtauieaniv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtptxdbvoc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigufen.top/Article/details/gtvhltimix.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtmlmiphql.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtnlqmryuo.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtqmutwjdg.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gtctapitkj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtxfqyrizg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtrkcgrviu.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtcijyiphv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtzhxxedpo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtrzxrpxpv.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtfycrxpwa.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrbyphqs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtdkyqhets.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gtomgysfcq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejkekgtm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavnellzv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtjqzlaeaq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtijdkcrmp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gtyjqqljmm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtuanmwmgu.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtehcutkib.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtqggjoode.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtiwbgiwcw.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gteiexvplc.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtbzeukwuj.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gthrtddfnu.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtidzxrjsg.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtusmuacnb.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtjqjfwrge.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtcetzxmxv.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtrdtbguow.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtxcufzwsl.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtnxvjcsza.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gthcqfinsg.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtsldlqaog.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtwbhivgxb.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtscpsxada.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtxijddglb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsrsvytlz.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtwttcyudm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbevbeysz.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtjpklutgy.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtzkddhmwy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtnxvjaqxi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtzkqorcny.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtruwdbzea.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtqgcuhxxp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtcksvojbz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtyipqmnft.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzxxxfqhd.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtxnfdqhhw.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtfjglewmt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gtjnxrdbkb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtoomtxctn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtiymluabp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gtaywiwyiw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtucrthaas.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtvfhiuiip.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtavsxzjib.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvzvumlzy.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbdesgfh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gtrhmcjzoe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtymkhwcfb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtuxdxuwpy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtceiqxfnr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtlrodhvsd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtdalyuqhv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gtilssekit.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtklekdxnc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbdbslae.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gtpmzekoxd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlofvfsvn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtexbuvbwk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtabbbqvzd.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtuhyqudkk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtubgduyrv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtmlusufuz.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gtdvllyofc.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtjhwuqcvz.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gtblguqmyc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtuqnakmwc.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbfhfqhm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtetjxdttt.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtjwwpwyrz.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gttgwymmcf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtwbyfwmiq.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gteezaxncg.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtdezvlfbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtdlvwhmoz.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtedeiufra.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtmmergkrq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtchsaspom.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtexnmckdc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtahmytzvp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtejmcravj.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtrbgmnwoz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtbzfawkfu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtjypqmd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtcprbafds.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmukqhehv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtyzjuktsz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gtpgevhfpe.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtgfwxmutp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtxzeodnzx.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtkwswpqde.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gttqzlxemu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtttuxwmth.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtxjwdrkgv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtdlqtqukx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtxmyubqcj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtfcaihnmx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxkwatpho.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtjxjkxuft.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtlrlsilua.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtmztywuzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtifppuznv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtusaatkvf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtmiechhdh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtyzkiikod.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtdewwlqxm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtzqexnhyg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtycwyycvs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtslpqqtof.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtqfnxudby.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtnhajvxgp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtappjgroj.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtiyauzbbw.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfqbjkeof.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqkkpyfm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtbwvcxdan.html


<!-- 参考信息 -->