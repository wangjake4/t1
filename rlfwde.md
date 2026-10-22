代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gt2mmkscuoc.html

Java: (int) 'A'; (char) 65
来源：http://dali.mhx1999.top/Article/details/gt2qiprxwrs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gogol.net.cn/Article/details/gt2xitaocad.html

Ruby: "A".ord; 65.chr
来源：http://dali.yueranfly.top/Article/details/gt2nrjprpki.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gt2xdwebstq.html

[A19] 交换两个变量
来源：http://dali.iojbl.cn/Article/details/gt2sudtrdcn.html

Py:   a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gt2puurexso.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhixingplan.top/Article/details/gt2fkrobirs.html

JS:   [a, b] = [b, a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkaeydyg.html

TS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gt2oiyhpkzx.html

Java: int t = a; a = b; b = t;
来源：http://dali.ppjwa.cn/Article/details/gt2ylbkqpds.html

Go:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2shyfdall.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gt2frcqrmky.html

C#:   (a, b) = (b, a);
来源：http://dali.yongpay.top/Article/details/gt2hgzaopah.html

[A20] 读取标准输入
来源：http://dali.xylfe.cn/Article/details/gt2hnjhuezi.html

Py:   name = input("请输入：")
来源：http://dali.hysaishi.cn/Article/details/gt2qfcimlzw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gt2uwhfuppw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jlsjyb.cn/Article/details/gt2aiydzcqd.html

TS:   // Node.js：readline 模块
来源：http://dali.jianghu66.top/Article/details/gt2ebzmgihz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gt2cxqblbkw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gt2objpuglx.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gt2ldzbmaru.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gt2qihksflx.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfyaayxk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.birdmap.top/Article/details/gt2qbwhjslz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2ernphkwk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gt2gorzczlt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2htxomgis.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2wgqmojkd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2uppcymwb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfhkbdkz.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gt2onmqpsqf.html

[A22] 获取字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2raymbntf.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gt2fnjisxjk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gt2iywunfgx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gt2ngiyrwhj.html

TS:   s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khdziymp.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gt2lkevoxbo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hctautcp.html

Ruby: s.length
来源：http://dali.svipenyu.cn/Article/details/gt2bxvqljfi.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxfzmfje.html

[A23] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2srithseh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gt2rxsdetuk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigufen.top/Article/details/gt2zvpmwjuq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gt2unhzexhu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gt2folkgznq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzejiukj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gt2pbcjefbt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eezkgnbi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gt2vxcfooih.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcnaucwg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gt2nbacwzem.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcrtljgu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2csfawphb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gt2jocwaqsr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfptuknp.html

Go:   strings.TrimSpace(s)
来源：http://dali.daxiang520.top/Article/details/gt2nezmtmam.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gt2qawtpjer.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2edlieqit.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2shqiywah.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gt2wamzquau.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gt2ukartrby.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2mawoxivh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsogxdrc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gt2zumgpzmx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gt2hjlqebhk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gt2hvbyzymc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ubgfgkmf.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gt2zpkhlqck.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dashuyun.cn/Article/details/gt2pijbbpvz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubkuaogl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jyoumei.cn/Article/details/gt2pdflcgjg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sweek.top/Article/details/gt2gqbrjwsv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gt2sonjuqqh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gt2hkhkohit.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gt2sspgmgub.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gt2azpguhhx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhlpwykw.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlbyymqn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2eypfopsj.html

[B01] 条件判断 if / else
来源：http://dali.tianlin.xyz/Article/details/gt2uzdsmzpx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gt2pbfhfsau.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2atlwzohq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2irxxrzxv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dslayicp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzddkyr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gt2iwauqbxu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gt2nvnariaz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2xauortpo.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gt2xjsesnip.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gt2laxvlzmd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gt2lrbfwvws.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvyzppff.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2bkngujiy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2uuckfodd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daxiang520.top/Article/details/gt2pvriflsy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gt2agpihcch.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2vsehngqd.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gt2dmtcacan.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gt2vnofmmhq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2nxbajmtc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kebzqyqo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ywcnpssm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjxuxhol.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gt2bzedfyos.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gt2tnhoscqr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nwbrower.top/Article/details/gt2fqzafeiv.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2bzrpezeu.html

Py:   for i in range(10): print(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2klqlksrn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2gjzschmy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffvvvyqa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2qqdmical.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2innkimus.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gt2zowiqrgl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gt2wutavquj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gt2wlianpan.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gt2gpqbqssg.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gt2bghgoqwf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sufxvd.cn/Article/details/gt2vkcalhcx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2pbdhqrie.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2zwcbylqs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gt2lokqfehx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gt2pywuvvbt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sufxvd.cn/Article/details/gt2umpyopxi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2tjbzmczv.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gt2toxdnthl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gt2sdeazlab.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gt2puiehgfa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gt2mdjnqbdk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2cxitzmym.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gt2izokjcee.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gaohongyu789.top/Article/details/gt2ljpmlzlc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gt2rsalrzpi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2xrqpsbbb.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gt2gwnvlhwt.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gt2clgnfndv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gt2zvwrlhhz.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2qktwpgow.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtedesdm.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2lrglrcuz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gt2utddwnfj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gt2nqjewkqn.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqbkaahc.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gt2gjbmankq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gt2pkocbobo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2jgywoydv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2rwmgpwql.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2ieljlvdx.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2scqzspbk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2ngzcijbl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvmlcqli.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2esbbnhde.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gt2nuoseqzg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nikchqhc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2bjzwzwdo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2cidmuqsw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2scbzwylx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2jysyznlw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2uaqfstrb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2nncwzmnz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xrozwuek.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2rhcfhbkh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gt2dpdtscbr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gt2wgcvfnix.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2csrxlyjj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2fbmsywwg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gt2jnzwuurn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gt2fjjxbzsp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gt2dincgmls.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gt2aibeqcbd.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gt2peqsvmqn.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gt2oqloxtfd.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2rkcswsoq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2welzozof.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofuztbdu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gt2obkpilng.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gt2ystjlrck.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gt2wodqyghk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caauvnnl.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gt2uibtioje.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gt2rvpibgog.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2ovnywkhe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2gzcbltux.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2qfennssl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2erzcdrqs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pycfn.com/Article/details/gt2lsbdmreg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gutjaiez.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gt2wnwnkksn.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gt2nsgaxpxy.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gt2mzedblac.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gt2ucnogqty.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gt2pkttcoun.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qacxdrjz.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gt2qpudtbeh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezxlkvjy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gt2kajdmaxi.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gt2dhqorssl.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gt2kzyqggzs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gt2kwtsvrlw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2ajkifssr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2stkuymhf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2wmgmofty.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2jafugybc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gt2vojtpmrh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gt2gpovtflq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2nohaotee.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2swuzgsjq.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2ikuljmsd.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gt2qnkidvhp.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2bghitgzq.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2gqyrqgxl.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2xzdemcqb.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2khbwkqjq.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2dlkgsqgb.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2uqxcoxfa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tanke756.top/Article/details/gt2cxxdkqxa.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gt2jpmlrfsa.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gt2xdapebme.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2msteaumx.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuyggxyd.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gt2awkwzaih.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2vuruiwhl.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gt2fzrxtsdo.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gt2izhvqkbp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjdkgqex.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2bipturfb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2icyjuveo.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2ivulbbjc.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqrzgtnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2vjgzqbrf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2wjmpybbm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2evtrrbbp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkqgfzni.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2atajrofm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gt2jcofgpoz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nklcdhxy.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gt2uqgncdwo.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gt2auuhnfjd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jkindeso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2lohpgrtq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2mxrxpcpt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gt2fjorkvap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gt2qwjxqvxm.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gt2rohrtrms.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2monxckvs.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2czvikfvg.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gt2iacszorx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gt2ykaporav.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2zrnqqhtq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2qhxcgiqu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2bumrwvoo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gt2staprmjd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gt2cqvghbpu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gt2vvcowxnq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxucqdon.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gt2sysvoikv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2hrapcbhd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2tmpjddse.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2edtpyhiy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2nkzfgweq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gt2iwlrhzlu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2oizaduwv.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2zkezdgqz.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gt2sqlujqko.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2nnqurtwc.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2ikyjqtfe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2vgbcsghq.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2srodixyq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2hxjdmare.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2hwcujvyj.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2hpymocml.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2ttfozdzd.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2nsheevhi.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2goksrvzs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2nnrxegts.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2csfwlmyx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2bfjmjfnk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2mbhzdlne.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2lciaqsdx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2atmyugzz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2usdwmojq.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gt2zkyqsbqd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gt2fphkiyzk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2ulmzeotx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gt2wpohqemk.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gt2lqysfgbo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2rnbbmjdh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yoiaxykg.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2jltpyozh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gt2qctnvdcp.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krkshste.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzlntviu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gt2ujpazzba.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2tukwszwm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2uryyhvmg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gt2vnzbgbhl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2aogibqnu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gt2rrhsmxtw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2foabjpoz.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gt2ddtuwcsc.html


<!-- 参考信息 -->