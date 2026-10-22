代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.snrcjt.cn/Article/details/gt2ibckmfrp.html

Py:   ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gt2omchjylk.html

PHP:  ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gt2ugbdpaav.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sysykeji.top/Article/details/gt2inkslpyb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gt2xeqdpbnc.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gt2cdrcmlmp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exfcnjhl.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gt2nvyeilsv.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gt2ekzabugd.html

[A19] 交换两个变量
来源：http://dali.jinqigfzy.top/Article/details/gt2hhavqftw.html

Py:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2cdtwefhf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cashguo.top/Article/details/gt2xigfmmwl.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gt2qqkvvvht.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gt2sccvrvqr.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258888.top/Article/details/gt2yakqboap.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gt2tlarlahp.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gt2mmoxsyzh.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gt2ejgjvjvs.html

[A20] 读取标准输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfrzljcd.html

Py:   name = input("请输入：")
来源：http://dali.hysaishi.cn/Article/details/gt2bdhrhmgg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cdnleiting.top/Article/details/gt2ikxboxpo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gt2tfroksdb.html

TS:   // Node.js：readline 模块
来源：http://dali.ydzc1.top/Article/details/gt2zyhptsoy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gt2bgvixwdb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gt2xsxdenrr.html

Ruby: gets.chomp
来源：http://dali.gaohongyu789.top/Article/details/gt2mwojnlmk.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gt2esouhbka.html

[A21] 保留指定小数位输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgyccwfw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.meibo888.top/Article/details/gt2doylijsw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2iontcxuf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqbgfltd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gt2lqbxqjlb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2rxgzeysb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2qluwythf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2sgdhvrba.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxuanxn.top/Article/details/gt2wrsuntgh.html

[A22] 获取字符串长度
来源：http://dali.hammf.cn/Article/details/gt2kuasethw.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ltzkdadd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.meibo888.top/Article/details/gt2tslmndwi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gaohongyu789.top/Article/details/gt2smzjqcqx.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2iemshroi.html

Java: s.length()
来源：http://dali.sweek.top/Article/details/gt2xnitbuxw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fptwgaxx.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2vhsbexuh.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gt2huvoeqlc.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2twijfxyk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2yqvxlyus.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guannengcc.top/Article/details/gt2urtojyit.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2ybkcttpt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2hplilfnq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2ifcmtghd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoknpptv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2nioqhruz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahapwcxe.html

[A24] 去除首尾空白
来源：http://dali.xinyue.icu/Article/details/gt2tkkjnicu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gt2rmpamwrf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.birdmap.top/Article/details/gt2pvqurnff.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gt2hzovjzrv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2ggaxewrn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gt2nyoccukl.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gt2obnxkpdo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gt2bsrladoc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2fxqkowrm.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2arafkeco.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gt2buiousao.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtevzbw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2moptuggl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2ztjtzztn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gt2iqllsjta.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvnaqgyk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eenmtoar.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2midfzadv.html

[A26] 类型转换总览
来源：http://dali.316326.xyz/Article/details/gt2xwofijdw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gt2vkczopkv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gt2jhdoraow.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndqdnpaw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gt2pgsrewvy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2cztgahrx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhengqikj.top/Article/details/gt2qcvzhwgm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ehwqpu.com/Article/details/gt2ufjlvabq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gt2zfkeltgo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2iiddkict.html

B. 流程控制
来源：http://dali.yj20258888.top/Article/details/gt2qqoljfti.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqsxijwj.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gt2eozqkgyo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gt2lkhjotdp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oschuruc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gt2ploihsmf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxeswapk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2ylhageim.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gt2hgdlwfyv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwldudcn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhxzojhz.html

[B02] 多分支 else if / elif
来源：http://dali.fzhhl.top/Article/details/gt2qcwebjna.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gt2rzyhgpzy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2omjzbasz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2ceyfcikt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gt2wxxelkab.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgcrtcvm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gt2vkfvwbuz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gt2tdpxjdga.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkpjfrpx.html

[B03] switch / match / case
来源：http://dali.mhx1999.top/Article/details/gt2dwszdzwo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ivvv.top/Article/details/gt2jochradg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2kpbgmerz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2vkxdmxzr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2sohxwiki.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arjklcej.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2uiagtulr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.smart0.xyz/Article/details/gt2spzeozmd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258.top/Article/details/gt2wzfmtbtb.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fefqoegu.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gt2ntzbscsw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gt2goxnsdrs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gt2uomhfyid.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2srmraina.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2jhkgvsfr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2oyibwzhb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmvbuwdn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gt2hnstyoik.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heieatzc.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcqrmbzs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigufen.top/Article/details/gt2fndyhxdd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2tgxdwpox.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gt2qfruxayv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gt2kotcvmnp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gt2fqkiwpuc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gt2ephvmngg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gt2xwctlccn.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gt2bndicjeh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gt2gexitzag.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gt2prqqvmea.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2grdzdhfx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbprvooj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sxryk.cn/Article/details/gt2smknxwvm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gt2mcwvdodf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.andypj.xyz/Article/details/gt2jmsxekvd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gt2aiqkerkp.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gt2nusvlrvb.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ubefokfv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gircmyof.html

JS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2vsghbeby.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2nxlohald.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzklaeis.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gt2vummylcl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gt2iplaywdk.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2yjdbzecf.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gt2iogzsfcb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gt2qcyalwtu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2mzlzzumb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwyvhcyj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2majakrms.html

Java: do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2heopkigt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2aukgswkv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tianlin.xyz/Article/details/gt2kmgwpbko.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2fuinuygv.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gt2ylrcvrbm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2czxxmdqh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2ohrzskph.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2lkdusotu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2wdhljfkd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2abcaqkut.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gt2rvthbkji.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2rctbvhna.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2antjrntd.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gt2opqrqjep.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gt2vxznfgmq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zzrwoamk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gt2qwbtrnwq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2cfxlcklo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gt2bdklixgs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gt2iixrlwxi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2jzbupldh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ighrssqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gt2xukrankk.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gt2nzzwfyuh.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ugdiukue.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gt2yhjiubnz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2klfhblot.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gt2caffcmyp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gt2rdhbsvzt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2jehjlllx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gt2shbbozjn.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gt2pdjitcqe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gt2wuyfccbr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gt2vsxgfgoz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2clzwivza.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2frbtcgvc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2gtxdulha.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gt2gunkfqon.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gt2pmvwmnus.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gt2hjoktsaz.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gt2dsfxalwt.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2zpxqijcq.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gt2boohhlbp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2kraeboxw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gt2wvfqescq.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gt2ltwzftez.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ishlhkke.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gt2scseajow.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gt2ecxhvbxa.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2untnmxdy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigfzy.top/Article/details/gt2khtfhkte.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2kikqqjqr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2qleesnem.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2dfbmnurx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2tjkqzhks.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2trcunnel.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2yypdlpse.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2xlxfljsz.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gt2vfcaqqnt.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2dbcimqyn.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gt2ebsifurd.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2rxpdgysk.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2cbsfmpfs.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2hjouvtjb.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2mvmkqcov.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2zjfehlvl.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2vxzzrfuo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpefjkez.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2uazbagox.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gt2pmouplen.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gt2swuadxzs.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2adswnrbg.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2txfnzaem.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzefapgc.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gt2erryugcl.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gt2kfqftvlr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ehewzqfq.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcavhjzn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dydkrouw.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmscgbjd.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gt2opxyvmfw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2juvhvwpy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ejfvufhv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2erwxyzmw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xregmzla.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2vhxrqhgj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gt2lmulsupx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2rxrzqosb.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kflxrdla.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gt2bzgpsmqw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gt2ufxgcqoy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2fkkqfpoe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzgzrttj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gt2oqhlftxl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gt2dxpoahvl.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gt2fdkvolbv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2nkgkhmuu.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2cmrpcxyb.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gt2kwtvasbo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2xdiboyjr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2tvncyscu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gt2wvtesfym.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gt2qhqgompv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gt2hrprwnan.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2ouldrizy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2qphlivhj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkifeaix.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjbqobdp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gt2lpgerymt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2xplcrusz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2okbeuhzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bysakevv.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2bmmlxiuy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2vyyxbhch.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2hojfgeth.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gt2zcqubjea.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2nypqljwx.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gt2nugfedpn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2jszbylmd.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2zuhcttra.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gt2nnosyhrk.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2soybynij.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2nuvuhsej.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gt2fnkkhngq.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gt2gleputks.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2ctqzrtbl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2yvuleiec.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2bworwcez.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2guakpcub.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2datalwrj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2lbmavnlf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gt2nemubvbf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2nvgqbkqw.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2bhsdcuix.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gt2mzjqldyi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxiggzaf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcebhhvr.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2fcxodfti.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucdmslvx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gt2phlpbtvh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gt2ryhsobek.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apupbvwj.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gt2jhqrpjki.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2dsirtgtv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vvxuqown.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jmaaviby.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2tpdphaet.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gt2lobfzbtr.html


<!-- 参考信息 -->