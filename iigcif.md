代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenlongwang.top/Article/details/gtypxkzksj.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gtbsixovzg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenzaomai.com/Article/details/gtpocjufri.html

Ruby: "A".ord; 65.chr
来源：http://dali.cucudq.cn/Article/details/gtvmdkfdgp.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigfzy.top/Article/details/gtzagrqhyu.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqptmnau.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtsjxyrhak.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhiwuduotai.top/Article/details/gtsytjwusd.html

JS:   [a, b] = [b, a];
来源：http://dali.smart0.xyz/Article/details/gtfogxryqx.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqhwrnsg.html

Java: int t = a; a = b; b = t;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmyduyqu.html

Go:   a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtelcifreg.html

Ruby: a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtdzpbwxfg.html

C#:   (a, b) = (b, a);
来源：http://dali.cheryme.top/Article/details/gtrzooihbe.html

[A20] 读取标准输入
来源：http://dali.vqdsnc.cn/Article/details/gtibjcdtlk.html

Py:   name = input("请输入：")
来源：http://dali.guannengcc.top/Article/details/gtqzxejjtp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hnqzz.top/Article/details/gtaqfzyqyo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.havefunace.top/Article/details/gtmwlixinz.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gtzoncwxoh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sufxvd.cn/Article/details/gtczufhikk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cdnleiting.top/Article/details/gtwralvajd.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gtwqfrqvch.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gtzcovibre.html

[A21] 保留指定小数位输出
来源：http://dali.wangshuangyany.cn/Article/details/gtfwarovuo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gtuhnhdcuh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxaewbvh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldujwayc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtuqxzpbgr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtirrjicuy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjwtjewj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtaewabfke.html

C#:   3.14159.ToString("F2")
来源：http://dali.snrcjt.cn/Article/details/gtbhrzrrly.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gtmfpalfgm.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtxiltmvee.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtvhlyduua.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtynqzesbz.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtgewefykg.html

Java: s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtkjfmlgkc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gtmcoysvza.html

Ruby: s.length
来源：http://dali.guowangkeji.top/Article/details/gtydnbrxmi.html

C#:   s.Length
来源：http://dali.hfpthk.cn/Article/details/gtntdfkxrw.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtskmldpmo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aibaodan.cn/Article/details/gtzcnrnola.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gtlgbdewof.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtynzjctde.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtpdaotyee.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtwvyckzhu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aizwys.cn/Article/details/gtjbllnpqt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtwrkmyoer.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gtdmcqzvut.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gttgcrttuy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenzaomai.com/Article/details/gtmywxzapq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtrkrvkqna.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtqmgstzxv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gttzowpfok.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gtrfkqhiad.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gtqolwaijl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtajollbbh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtdnntbrir.html

[A25] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtletdskxw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.meibo888.top/Article/details/gtojxocpvl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtdvxhxbdh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtccykmolk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtozzccvaf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtnxioyjdz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtbuimikkw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sufxvd.cn/Article/details/gtbdmelgyl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtodfpfmci.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtnmzyoobl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gtqhnudcqe.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtsqhxlvqh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gtkzczrjol.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gtihceuckj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtigzqchya.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtauyqltfu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gtqaoaifwd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtmltermxp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlfohvtct.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gtrnuxukdk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfgvfgtkw.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gtpfmwqrmr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtfueexcit.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigufen.top/Article/details/gtcacchqih.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqcchmsz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtenjknhfz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtmgtkzpva.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.c1oappe.top/Article/details/gtlrbzjceb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtwxlsnssc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gtbpkjaohy.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gtoapdafeo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.meibo888.top/Article/details/gtbrpuacxf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.redwolf501.top/Article/details/gtjpiybnkl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtwhpfxwjs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcfkyojg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtxjczyjfa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiztljjz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tianlin.xyz/Article/details/gtkicdgvpl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtprkmquzt.html

[B03] switch / match / case
来源：http://dali.hnxiangtu.top/Article/details/gtfvdpncir.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtjzihcbvq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtcpmeubrn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtzxzwnuto.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtpwbtiqxd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtwxwjvuhh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gtysmtrwuz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daria6918.cn/Article/details/gtxfkgfzwp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtfchonftm.html

[B04] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtutzfzkjl.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtfegkjtwu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuhvzeox.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gthhoyfgyq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtzknxophs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shzxlz.cn/Article/details/gtczssjupu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtyzwwxoxx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkzjbttt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtiykzvtht.html

[B05] 遍历数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtnillqgsj.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjlnfipc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gtdlxfipyw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gthrfvtbth.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtpjuuutoz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gtddybobzl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtozwlzuun.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtbyygqnkt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtpccsckdr.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gtozwfdawz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtzrgyhyiq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtulwvtwrb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtczzwhhfj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gthfchmubd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nwbrower.top/Article/details/gtclpdtkbr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gtgqakmxek.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtrknnslge.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gtmiyssqvq.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gtlkuvhspf.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gtnelvfquh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gtifhmqjpq.html

JS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdhnqfhh.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gthkhrjbxy.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gttbxfyfut.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtjzkeiubw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtucxrwunw.html

C#:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtuqbvryed.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gtlzrpjmhl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gtgyidxvmp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gteqivpqii.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtyvnjuruy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtbpulgikf.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtsarazbsa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gtogyieqtk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtumyfdppi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtegxvrzhc.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtghntfoiv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtsltqvzoh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtdiuaaoau.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtbiwlmcfo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtowyzikly.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtemcqrjee.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gtsebgjlqr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtadmvimcr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwfbtybs.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtnrwpaztv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtyjgzrael.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.andypj.xyz/Article/details/gtzhfldlnb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtofutoazw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtakrvjjac.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtyfdjzdxz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtgbhibyjp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtynzqhfth.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtagrimzrp.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtgdgjcxhp.html

Py:   list(range(0, 10, 2))
来源：http://dali.yanxiufei.cn/Article/details/gtwdekhdhf.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtkdxojywt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtycihvblm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtclszxzbg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtugulpdja.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtglwcnhqv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtslgjhqii.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gthqitgvuz.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygemjeyi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gtujoobouv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtvhnljbma.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtxupihotp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtfhibrmcm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtzwftynxk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtyzxivrhh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtgjssuurq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtmzexhbhq.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtaiidgkxy.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtvylvimau.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gtujyzhoou.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwohoeogl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gttrghendj.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtacyrydlh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gtvwcqqcbe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gturaislvo.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtjjdsmlll.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtlkacsxvr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gthctgwyvk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtsqlijvky.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutdkvioh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtilouzyko.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtluwduhnq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtlufjgvjj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gtdduehfvw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtjeskagpy.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtcdlhckay.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtyeupwjim.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsngiawzp.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gttyvilmxv.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtsvyappqy.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtomhnsyvv.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gthimwerxi.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gteakyerfn.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtmrsehpey.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gtstjtqrun.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gtdawiwabw.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtjfkobhgz.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtsffeuzvm.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtpmqoiidu.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtfpzhdkha.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gtadgouwqi.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtsnbfpzmb.html

C#:   if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtilezsxub.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvcoavyrc.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtbugszrby.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzdolcjvo.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtskjtszjq.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtbjoalmeu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtnghoxvra.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtsogcvtua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtuksygxbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gthyraeqmc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtnhybkwcc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtdujtzizk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtjnupgzav.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtnftlvlid.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtervmjmqf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtbwcxejhx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtyvtkznxp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtuowtadww.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtxcztltyt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtmbeojgcp.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclpmhvli.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtrydfvyqu.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtipqftaru.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtdkikdgwe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtaemmiatm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtpjecmhsq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtovlkqkuc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtelynduzu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtbphmrwwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtefvhoisq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhwfisne.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtlaenkxkz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtiatvsjhv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtqaspzfyh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqdamaeew.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtngisgvgt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtdfwlmvee.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtetmsuzgb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gttkjfizom.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtahqfwlkq.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwverrelr.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gttxayrbke.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtyxaoosoh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtsnucggag.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtdygyuixc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtmyjgvmkz.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtvdctokgu.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtdigwldsz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtfflailce.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtwejzkqyb.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtcgllovrh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtjztdduqj.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtggvzludn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtspczycda.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtiarjamdt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtbekbizuc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtfsylufiw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtijvlbhhu.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gttvsyliob.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtbftpmbkh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxfvmkgy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtgcxbgtqh.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtgbkdiclv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtvtecyuop.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtupzzanxj.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtepwoeqtq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtkecezptc.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtvxjndppr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtungcxzhk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gtmtuzagxs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gttdvjolke.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtkdmxksze.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtwmvqamso.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gtfuicdbpz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtlmnvnzii.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtqbtsakuv.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpixnhql.html


<!-- 参考信息 -->