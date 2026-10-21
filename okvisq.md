代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gtsldzmsqs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tianlin.xyz/Article/details/gtjarrtcbk.html

TS:   if (!x) {}
来源：http://dali.zhoulong.xyz/Article/details/gtetksflyf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgreujfzz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gaohongyu789.top/Article/details/gtqvzjrxfg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ybcxt.top/Article/details/gtuiceztke.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gtxnjidsrl.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gtzhhqaktd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtwmexhqdi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.bjfxy.top/Article/details/gthyfhzwhc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gthpgmaxkl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtxkzbgfiz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtbjbloszy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtafoxfmel.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtmsnqcpwc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtrzfzxhgh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgufenzy.top/Article/details/gtuzxedser.html

Py:   ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gtfvgkborv.html

PHP:  ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtosdzeutr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gthfuotfly.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtmsgywhil.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gtbdicetjs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gtqvpdzeqi.html

Ruby: "A".ord; 65.chr
来源：http://dali.hysaishi.cn/Article/details/gtqlnfhjoj.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gtztlhaxit.html

[A19] 交换两个变量
来源：http://dali.zhongyouzk.top/Article/details/gtinllefem.html

Py:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtoenxezqr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gtcdfqdfoe.html

JS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gtatbemtpq.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtxljjwkgn.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gtcvrvnolw.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtnmptlfqq.html

Ruby: a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbyxradx.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gtbzfilnji.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gtdyfwufux.html

Py:   name = input("请输入：")
来源：http://dali.cucudq.cn/Article/details/gtlqwjesig.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gtgifiqpbl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daria6918.cn/Article/details/gtjjjqdwxd.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gtstbyxhkj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.snrcjt.cn/Article/details/gtgrpedwje.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gtswehvvdo.html

Ruby: gets.chomp
来源：http://dali.nanxinkj.top/Article/details/gtjsicrons.html

C#:   Console.ReadLine();
来源：http://dali.zhixingplan.top/Article/details/gtrrljzzve.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvgkthwd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtcqkmzddk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzljagazd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtgfqxtrmt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtxsgrrunq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtbvplprqx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtuxrwhljt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtxkzmleam.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gtrnnoyzsl.html

[A22] 获取字符串长度
来源：http://dali.zdqjudy.top/Article/details/gturyulyjb.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtufuzgowv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gtlinxyroh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jlsjyb.cn/Article/details/gtxgtxwmar.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gtnevklsws.html

Java: s.length()
来源：http://dali.hysaishi.cn/Article/details/gtobyulqda.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.snrcjt.cn/Article/details/gtagmvvjjg.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtnzxfvrrk.html

C#:   s.Length
来源：http://dali.smart0.xyz/Article/details/gtljsjtkxv.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtrosdotqs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gtjlomiyux.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtjykytoky.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtlejhncsc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtdpfevjqw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtvriciobd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258.top/Article/details/gtcwbrupma.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtkqdsdxvx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gtaijgtfhl.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gtpreybypl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtxqyvynke.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gttlnrpluv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtalxkltab.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmukkwm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.kuanghao11.cn/Article/details/gtbxqlnuaa.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gtecflrfxo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gtvidyaudq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gtxbwznypc.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtuegsibtb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hywenlv.cn/Article/details/gthsofbxie.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gteuguimsl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gthltodmzr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtqwfkrrjy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gtlnntlsih.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gtzhxiyooe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gtrmyertcv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzcmzxbh.html

[A26] 类型转换总览
来源：http://dali.yuxming.cn/Article/details/gtwehdpcwn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gtmwldhhly.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtgfmqzlrv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gthvgrtuot.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gtmjllwjed.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gtduuksqar.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gtnridzbnk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gtcphehmla.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gttkhhdisj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtapshfnod.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtlhiqavmm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdlfrdqhi.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gtzwrugzuh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtwevwlpva.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxbxhoyl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtagdtfyuw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtfamtanux.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtotcikhhl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jlsjyb.cn/Article/details/gtyodxkqji.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtnfywfiwe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtjynrearp.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gtudcunlzk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gtztotcvxp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.316326.xyz/Article/details/gtfsybahrt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtppexifvl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtbxwspkwa.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtkfzqxwcd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtzbplsqmt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthypvczau.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtwoiqmayo.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtaixaeozd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtlbbkkpal.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtwheluswf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrcwlcayr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtnioarbjn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtihoexeln.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtefwdhuwv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gthvvvzrgh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtvjgrttwh.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtiacqmwpv.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtucjxgico.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtzjtzyvjb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtpfqkjhyj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtlrsmciyx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtxljsvrrx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gtqxfnhypw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtkzmwlxer.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnrkccpgr.html

[B05] 遍历数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtbsxajrxl.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtarvcfqqz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtxaipsxcy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfjxerots.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtftoczsaa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gtpxtnuasy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gtyovvwqjo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenqwzmnj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gtjgxjtrop.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gttkxtjyxa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggcaswdz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtiivyslhe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtwhptbetv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtwhipsvje.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuanzhike.top/Article/details/gtimapjtfj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfzdmsugr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtpnjodwam.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hywenlv.cn/Article/details/gtiqhvfveg.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gtqozuzndr.html

Py:   while i < 10: i += 1
来源：http://dali.cheryme.top/Article/details/gtowumqfqu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.smart0.xyz/Article/details/gtzihygsqg.html

JS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtamzejhxm.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtcnudcyqc.html

Java: while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtfqjlhalg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gttvihbizj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gtoamfafwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gttpaleyfj.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtroawatcu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtayewnoaz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtroewtyao.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gthjudzgvo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtmwubodto.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtgfozytpw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gtplxvarde.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.vqdsnc.cn/Article/details/gtwpdmmcbr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtdgajrxnw.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gtxujfosok.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtgrebjvqj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gticfelxzu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gthmetigie.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtuhlwiwqd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtqmamefty.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtrmgxixue.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gthbvlttvo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtopsfdokh.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtessnmwkc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjlprwpb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gtmexzzisl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtignnhffc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtwepxtcmi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyheuuiml.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtycemobdk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gtqdtwzwzg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtgoiqaqzk.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtikhukqdo.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtqqqtettq.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtlvyvgyab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazljxxrb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtwmryzwti.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtgyiitlms.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtrtvpsrpz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtqttvggjw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtmhrsfung.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtkkjieknt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtojtdzujh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtilkvmpmu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtudwuwhoq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtkqscyfgv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtaoyqaehe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtlfdhswib.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtbrycvpje.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtsxaqeztp.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtasxbjajn.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskmiumok.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gtxqqkfrjg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gttyzjrgft.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtjrxumpas.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtlmidxazn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gticcqygfy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtqybtjegj.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtbujvwats.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gtdoekwbnk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtzqjpdysx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtkpfniqon.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsotwwmau.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtdhxemzcd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gtygchgswg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtdtfpsrxb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtdiykaqmr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtprpcchpz.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhgaovds.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtqrahxhow.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtnbnnltql.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtvkugeipx.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtofvjwpnj.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtlynxgsox.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtceuhtyrv.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtpssopgtu.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtbrvwwmxi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtleigstfn.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtyfmayqky.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtpedczmrz.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtlzcnbsxs.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gturjixtfe.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtznyjyavu.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtexuxktsp.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gtoobrmbaj.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtfqtzvgtt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtagdkoknc.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtpiihsuoo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmongugsh.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gttovoufgm.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfhkaxfy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcwphonnc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqiuaiuw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugfidyqt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtyznowybz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtldgoumzv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtosiixwuq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtpgjaxcgm.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gthqeuyzxh.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtrldkcbss.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyuxemoey.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtriknipur.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtehsnspjn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtrqjqogtq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtbdzumtlo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gtanxtvcms.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtabiqdfol.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtygpuapqj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtrxhoivwk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtercongxm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtndaxykae.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtunhumxie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtivaakukx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtniiteqvt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtckzaildz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtlcjhgimt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gttwxmqmez.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtqwqivbro.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtvbalzdih.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gthujyrtzy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtuhjpqbvm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexivdypo.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtpndzpsae.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtmfwdyygq.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtjqosypnp.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtqaammujy.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatvkcztb.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtsdgjtrxu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtwfhyobfp.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtwpgrsaoe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtcdmjedti.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtxwwqeewv.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gtomowpgcq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtjcftidxx.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gtjgcrfegf.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gtpnyfgfkr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gtsfqywofe.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtagnlzrbq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtwizjocfv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtqybsunwv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gtzsmmydjo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtywbpcapm.html


<!-- 参考信息 -->