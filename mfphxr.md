代发 wailian999

C#:   (int)'A'; (char)65
来源：http://dali.aibaodan.cn/Article/details/gtndgvhsmw.html

[A19] 交换两个变量
来源：http://dali.andypj.xyz/Article/details/gtoaotrhyb.html

Py:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gttghissdl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtcvukydpk.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gtnmipiqhp.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gtrpowtqwq.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenzaomai.com/Article/details/gtvoosntaj.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtmlxcfpoi.html

Ruby: a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtqigwkipm.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gtqhvfhrjz.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gtlibbhttx.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gtnhzsubbi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgfzy.top/Article/details/gthrfhlfrq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxinkj.top/Article/details/gtlxuahomp.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gtvpgzeiso.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtvsncdufe.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gtjxkpqqzz.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gtuytnwrwf.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtupnqlksj.html

[A21] 保留指定小数位输出
来源：http://dali.ivvv.top/Article/details/gtphjerxaj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabbfxvuw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtgcyifcpb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvkkziax.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtbvcrhgpz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtdelradfe.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtbcnfitlc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtyryepkyv.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvyswxsq.html

[A22] 获取字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtnkcyhstr.html

Py:   len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnamgdxdu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ehwqpu.com/Article/details/gtytxjkhvt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtkalmcxfn.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gtvtslllzc.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtnlogbjrm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtravhrfqc.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gthalvfabi.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gtevutthya.html

[A23] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtwrtmrzdo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtweexcoar.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhongyouzk.top/Article/details/gttroyedeh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtbknnfcjx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtcejynwzf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gthyhlzkqr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtrtwwvixt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtumjopsan.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnxiangtu.top/Article/details/gtcvlqyylr.html

[A24] 去除首尾空白
来源：http://dali.andypj.xyz/Article/details/gtqgvklghl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.meibo888.top/Article/details/gtmpaxseut.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xylfe.cn/Article/details/gtmhocwsmq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtmunxffyl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtunkkftzv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hongshengwenyu.top/Article/details/gtkaxvzrzk.html

Go:   strings.TrimSpace(s)
来源：http://dali.cucudq.cn/Article/details/gtzsussafl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yueranfly.top/Article/details/gthratsggy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yonumen.top/Article/details/gttujdauxj.html

[A25] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtvltxjscw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gtvatuevmc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.smart0.xyz/Article/details/gtphosaler.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtxdqmxipi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gthbglyfgs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gttczksbyv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtmdovcymm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258888.top/Article/details/gtfiihqkbi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtsxlmdzba.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtykoarify.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gtyecnkiqi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gtmmxwuwdf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gtgzgorefh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gtqalfmqnl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtlbosemoi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtlitqvkru.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtpndybkdq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtkmzhpqrf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpkiqnsur.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gttvivpqly.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtguifiwrn.html

[B01] 条件判断 if / else
来源：http://dali.jinqigufen.top/Article/details/gtjgtdleub.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtsoxwkfob.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtzotifvkc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtytrppqkr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gthhozbzpy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtyoeufylp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhixingplan.top/Article/details/gtdhzfdiry.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtynzjldch.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtuasvronn.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gtlfwiuozn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gtondteofq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzkchfdmu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gttlcjtzjp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtksfdvric.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtjvspyuws.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuetiantiany.cn/Article/details/gttczggbjd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.andypj.xyz/Article/details/gtejgdkxbi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtknnzcntg.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtsitmwskg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hfpthk.cn/Article/details/gtdnruzaqx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gthpxdkhoj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gttuzuxkcm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvqrqnafo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiygcdlui.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtpamwgimr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtlugusreg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtuxokfyeo.html

[B04] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtdtelohpe.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtxsoszlsu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gtbicjtbfk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtloltkbtd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gthbpwlpeo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gteohvqqga.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtxlfowils.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gtgumvfpuu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gttvzdvobq.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthssvscpc.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gtcphfagos.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fengsongda.top/Article/details/gthvaquizy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtreafngwk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtwercohex.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtbctuygyr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gtikkpajpi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtnkvyvbqh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtfyzxjqzo.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gtijhaktko.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtckaolnyo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtxgflgjdb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtwobgvaof.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtctveskdi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtvradgtep.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtlibtlbhz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gtjwoyntlc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gtwytsyvxt.html

[B07] while 循环
来源：http://dali.smart0.xyz/Article/details/gtoluininh.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtzrdrmhqd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtrbhffysf.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtsdhcdxap.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtgfjisuoc.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtelmmdlii.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtctaqqzzt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gtwzpccofz.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtszzjwlls.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtpbghtkhl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gtdugzdkty.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtqzgcbcan.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtvnwmqpsz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtqjsjiukg.html

Java: do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzdkjooxy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gtyfxjebvm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwovieggr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtsnrdifzp.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtnrlffclm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gtqumxunrh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtgdqrbfxx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtymsrsiqw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwjtdtzgi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtlpbdelsj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtxqlwogaq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gthgflatxf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtieqetjlq.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gthvtyaiwz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gthruoluhe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtgzzqdjjf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtbjwpdcel.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtrpsdwcxe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtuvaqwwaw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtubhsgpqo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtfwoureht.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gtxkgltatk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtoynrfhek.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtdpgznbel.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtjtxohsmo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqqsqjau.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtdalchdjb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ivvv.top/Article/details/gttpkdgzyd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtgafkzlik.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtghimjzcr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtlwjmaifd.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtobufurjo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtqkddyaqe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtdntomrem.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtlyinrzns.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtvjmfmlfu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtljxdjdwi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtppfdvekg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gtlfleogpv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtasfsvpsa.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtpcptgrtl.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gtszaaifxn.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtnqduhfgx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtbcouacsv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gthfwocdjf.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtrwcfxmff.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtdkyszbxm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtuappwmna.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtvawqvtvt.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtafobkkvi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtfgixowth.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gtxrybturf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtnofhovnr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtcaytbzfe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtshjzlrmg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gtzfrrykkm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.iojbl.cn/Article/details/gtxllkegwp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtewdyvvov.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtinspcnds.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtndemefpb.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtcgsishds.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtjddfjofx.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtzfomrqhz.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtpdnwmdbx.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtkundalqn.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtnnxgasdu.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtphiadwbd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtnfivgqeg.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtolqngmlv.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtakxkntfz.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtestwqnnj.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtgvigjvjd.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gteytdbmup.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtiptmzijs.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gteczomush.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtxailcfmf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxkicvckh.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gtfqeowyhl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxiqylpyp.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtzowvgqnp.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtqiewyfjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtkxyyytbw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxaeglwtm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtpzxvvfvs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtqbgyimwu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gttimsoycc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtgaywfxpn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtbfmmapxq.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gtxgzqdyvd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtrsncbbhm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gttezuyxqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtayuirxpx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtnusbbzhw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtivnwxhoe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gtfcncvryv.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdclewhmf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtkshucwdy.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtdicxxbmg.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtzkropmel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtvxnmbvew.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiaesufhz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtlsgmigrn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtqrncrqqr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gteyfpmlvi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtaqkefnwz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtlweunmlw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gtdvczycrd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtrpcnqglx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtvlirdblr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrnlfqfed.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gtapmqtxbb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gturywboeb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtuhjhrxvc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtskjvmewf.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtuxytkplo.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtkjdntjoi.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtkplyvauc.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtsaugrfxp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtduynmuot.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtubntyozh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtkvrfclpb.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtaajexcdw.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtfxvrknjg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtlrqfdggq.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtmbrzjgth.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtazjognjg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtyvdqtvbq.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtlxtkjgci.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtluvozbgg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtfzgbnrgg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiytcwdh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtorwwkqyo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtpnngpiwj.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtwsaikzmi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnhpvdhj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtllarmtca.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtobzctklp.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtbgzxaitm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtaphphuik.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gttrnsddqy.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtnyagtaqq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtzanikovf.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtebqvfgfn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gtnjvgxzps.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtabkgumle.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtsavgcipi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtefsfbuma.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtcnkucfiu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtnnoenjxw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtrafanccd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtlqjkeyys.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtfulsxgog.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtitsrvbil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtmahmqqen.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtxbijtovs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gthesugizk.html


<!-- 参考信息 -->