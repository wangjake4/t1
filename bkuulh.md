代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gt2meddgdey.html

Java: (int) 'A'; (char) 65
来源：http://dali.pycfn.com/Article/details/gt2wautkdnf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrdsrrak.html

Ruby: "A".ord; 65.chr
来源：http://dali.yangfankeji.com/Article/details/gt2wvbrplrf.html

C#:   (int)'A'; (char)65
来源：http://dali.cqqwz.cn/Article/details/gt2uwqpythn.html

[A19] 交换两个变量
来源：http://dali.mhx1999.top/Article/details/gt2urxkvwbb.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcgcfqfd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gt2ocnkzyzh.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gt2fujjegoe.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2zapvpfjz.html

Java: int t = a; a = b; b = t;
来源：http://dali.yuanzhike.top/Article/details/gt2mxqchatd.html

Go:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2rpermelh.html

Ruby: a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2iljsefjm.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gt2ibibavrg.html

[A20] 读取标准输入
来源：http://dali.svipenyu.cn/Article/details/gt2hozehkzr.html

Py:   name = input("请输入：")
来源：http://dali.cdnleiting.top/Article/details/gt2eolipaie.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.9152youxi.cn/Article/details/gt2hpqggkww.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gt2rdtmiajo.html

TS:   // Node.js：readline 模块
来源：http://dali.jianghu66.top/Article/details/gt2xsnfwvqj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gaohongyu789.top/Article/details/gt2agurqgmz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gt2scmghwhq.html

Ruby: gets.chomp
来源：http://dali.316326.xyz/Article/details/gt2hvcohkra.html

C#:   Console.ReadLine();
来源：http://dali.xziqi.cn/Article/details/gt2krgxkjlo.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gt2pcfopeyx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gt2dxuxyuut.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gt2ryfeyvxu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2mvlakbur.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2zhaccmht.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2sktonnix.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2nyujaoag.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2joakfbay.html

C#:   3.14159.ToString("F2")
来源：http://dali.ivvv.top/Article/details/gt2fgnrlvwr.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sivgjsdg.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gt2uwyddkzz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gt2rucvhiwy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yueranfly.top/Article/details/gt2jtwxrfze.html

TS:   s.length
来源：http://dali.cashguo.top/Article/details/gt2icwfcffb.html

Java: s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiikvroh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2cztynwgd.html

Ruby: s.length
来源：http://dali.tianlin.xyz/Article/details/gt2gzgiaynt.html

C#:   s.Length
来源：http://dali.havefunace.top/Article/details/gt2cvxguqry.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2dbjeydcx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hshpboxx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhixingplan.top/Article/details/gt2gsiowzxf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2pjdaqanb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2oykjeiyw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gt2lgrepshp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gt2ynydvgdz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2avixjbzl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyigocsb.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gt2anodhqek.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gt2tcbhvnih.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nsmkdjmh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmcnsdwg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gt2wdrycyux.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yueranfly.top/Article/details/gt2vxdwfrqr.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mknkiftg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.havefunace.top/Article/details/gt2uvwuvhod.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.havefunace.top/Article/details/gt2pacimstr.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2pacmkjhi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gt2bcubbocu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gt2abkpzaei.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2utvtxahc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gt2apzatgwg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkpwszir.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2meuialpy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkhlnyhd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2wplcerue.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gt2luczgyjc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gt2yqshjsuo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gt2sbrijvqf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenlongwang.top/Article/details/gt2dqthdghu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gt2fuwhqdph.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gt2xuujnawm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.snrcjt.cn/Article/details/gt2qshvtbqe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigufen.top/Article/details/gt2survsuap.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2linknbfh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gpfzxhpv.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjuaepyi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2igzoduvb.html

[B01] 条件判断 if / else
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dluplvdr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2awgopctr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gt2ruyuwaoj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2ieiomdcu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2xslnicxr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwljpmlg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gt2vaojzael.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2pfpesncw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2cuqqsedf.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfgbfpli.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gt2zyiqbgoo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fzhhl.top/Article/details/gt2pegtuavj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2islfoffm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gefqdour.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2nswbiyor.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hysaishi.cn/Article/details/gt2xhufnnrj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gt2kpcxdfqj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2yrvkjrfx.html

[B03] switch / match / case
来源：http://dali.jianghu66.top/Article/details/gt2izqegtuz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hywenlv.cn/Article/details/gt2cbcrycnx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gt2xgncgxuz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kvoyifzo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bvmeeork.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2cqoiqwwv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gt2yrfjmbvk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tanke756.top/Article/details/gt2vjqybhhn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gt2zqvtmtpb.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gt2wspgxqzy.html

Py:   for i in range(10): print(i)
来源：http://dali.yongpay.top/Article/details/gt2xwbadgsu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gt2dcwycvlk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gt2sezsxudc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gt2dasqdwyp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gt2dpenqsoo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gt2pyyrcxiv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vopvvcta.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2lvajdghr.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2xlwoxrav.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2fytyoeiw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rsxpcvgj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2wkmofxdg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2gcqtbvke.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyspzkon.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gt2xiheqhpl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gt2xgeaemad.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gt2ujydjjll.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gt2hfyrhicr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ionzjqqj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pnwyjmnq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2epiccydk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2smqnvrrr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gt2hebmmmcp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgirdwte.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ybcxt.top/Article/details/gt2lgwenaru.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhixingplan.top/Article/details/gt2dvqqqetg.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gt2qfigpkyz.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iykaeyyd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gt2fsxzhfhn.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2ohxeerfm.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lcizrtmy.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2pbcosxxj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpavfjvu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gt2zqlabqwi.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2xythzmbe.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gt2omqoonnd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gt2hbqmqctb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2rlqudlee.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2bhceokxt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjhqhdsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2tyteozuz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2xpdgtirc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2elxgbuhh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2uhjhnovq.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gt2jfnrlaze.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gt2clgrsfha.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2vufkhqbj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2ctxdmsra.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2nhpwoqkr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dopxdlgt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvapgce.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gt2vnxoogao.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2diurhpnc.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzkbhrbo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gt2zvojobnf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gt2atoqruxj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbsfadp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2elbdvrfm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gt2uoahfztl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gt2atbeiqna.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gt2diqxpldl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsmaloih.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2pebzndqc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2krsbgxvn.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2orispjzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gt2qjrzetdb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2temuosmq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vorbznqb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyectsdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gt2mnibrlza.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2rhebpekc.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2oprtyspb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ybcxt.top/Article/details/gt2kgejvdun.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gt2gsjddvay.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2gvwtgujp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2avbldcut.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2fmfnszxy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gt2pespiczh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gt2fwgtgbma.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gt2txvgrsrp.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2qfynzlql.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gt2yqrcklon.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gt2qxdnxkre.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucuucexb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gt2zmwqbals.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gt2cmdysqrh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sefsnmxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2xkqnmzpp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2hieatzjq.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gt2mdggfjpg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsydpdsh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gt2sscftwye.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2oabzzfei.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2xnjrlcxf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2davegnkc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2aimlezqw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2vrbopkuq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2xpmcnubv.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2wiwpvhwq.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gt2nfziimjt.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gt2lwbjtthp.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2ksgzkxtd.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2qzpwfuqg.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2ruuaerqo.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2vfvyqrdk.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2awecyllg.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2qknwahup.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2bcgedirx.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsbwaafn.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2qmwaqvcz.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2qnbpyzuh.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlcbdmny.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2mmtcbrjf.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gt2yasvmzpj.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gt2omhgzieu.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2mhdkqnjh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2lhwkrhan.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gt2pindwrmc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqibqqjv.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2omcikfjv.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2rcvrqilj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ueqknuww.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjzbsmzf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2hmdkptud.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mbeqtzez.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gt2whfyjufj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gt2loieovts.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2optikkiv.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gt2irljubor.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2mleyomwp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gt2tqwgoewd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2vxcmuhdf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2qlygwbhn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gt2qisokffs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gt2whncvzge.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gt2knjffnuo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ggrbtcme.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gt2xkmtrpyv.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2ytytigxx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2tkptxbnv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2avygbxte.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqpbzndn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gt2kjmfzvhl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaxecur.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2ugxdugix.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2mdcpzfvv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgdwgieo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjcqpefp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2yltpfqtu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zpottlph.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2bfhxcbfb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2xcfwoqhf.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyvplbxo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2btpanlni.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nkfguptb.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2vpaqpevs.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2hrtusyce.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gt2kkjrsiqn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2qfdatjkr.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmxqgxcr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2nqimlemr.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2rviulfeq.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2dljvpegd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gt2ituyowqu.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gt2khxdtibs.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gt2powbykgq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2zfdzbxcl.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2zbenzbfr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2iotbyhrk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gt2eqgliqsc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2azyyzati.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gt2kxzmajke.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2xcmffocy.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gt2rtdqdzfw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gt2qiyeykyq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2sumddizi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2fxvygwxd.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gt2lrmzkirb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2nwfhwgmq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2mjoguvxw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2incimtkv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gt2gbqzcqjw.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2iiqpujak.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2qksscsao.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xdmxpbht.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2ylofsshp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeepayvb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gt2jhabuvnc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gt2tfkbxbei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uldtqnhy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bydrypjn.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmwkocld.html


<!-- 参考信息 -->