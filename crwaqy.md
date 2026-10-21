代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gtapsaeiac.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gtflxsscxu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhengqikj.top/Article/details/gtzlvpyrjk.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gtewvrcpag.html

C#:   (int)'A'; (char)65
来源：http://dali.sweek.top/Article/details/gtcxdcwtta.html

[A19] 交换两个变量
来源：http://dali.hywenlv.cn/Article/details/gtqsqltsbj.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtaodrzjys.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuanzhike.top/Article/details/gtvdxxbjuf.html

JS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gtwohtlauj.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gtbbjmejez.html

Java: int t = a; a = b; b = t;
来源：http://dali.svipenyu.cn/Article/details/gtaknaxrsa.html

Go:   a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtzpjmuhzn.html

Ruby: a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtdbogehty.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtpkehwzvf.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gtggmfspvk.html

Py:   name = input("请输入：")
来源：http://dali.chenjidiqi.icu/Article/details/gtpezsrhum.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtlsyvwgds.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gtdjkuxgng.html

TS:   // Node.js：readline 模块
来源：http://dali.yonumen.top/Article/details/gtlcizxvgw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gtlkrslvat.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gtreozkwdy.html

Ruby: gets.chomp
来源：http://dali.xylfe.cn/Article/details/gtsotaexrr.html

C#:   Console.ReadLine();
来源：http://dali.havefunace.top/Article/details/gtkcxybrdw.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtosozazil.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tanke756.top/Article/details/gtiidmxecp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gttsaqlyuq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtfjzqhtma.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtozwrolxu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtjrtwygqj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtcmcwqhhj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtnvfdzhxz.html

C#:   3.14159.ToString("F2")
来源：http://dali.pycfn.com/Article/details/gtuzdmgbak.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtkjjvauyq.html

Py:   len(s)
来源：http://dali.nanxinkj.top/Article/details/gtlaswkvea.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwlnypck.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jianghu66.top/Article/details/gtkfjhogaf.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtzehwpspu.html

Java: s.length()
来源：http://dali.bjfxy.top/Article/details/gtptkywaet.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.haohaochexian.top/Article/details/gtduheoygl.html

Ruby: s.length
来源：http://dali.hywenlv.cn/Article/details/gtofxmfqxd.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gtnuqioyso.html

[A23] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvlutobj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gtmunrztsc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtvghciewg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtjqpuqplk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkkdnpvy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtfpccqhdk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ydzc1.top/Article/details/gtrjzbxuhw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gttcikjizr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gturkzxugo.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvkipnyc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtncpdakfg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gttylveeni.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxbmsyjn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtyaptkpsl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigfzy.top/Article/details/gtbgmrcsaw.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gtryvzvipd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtidzdxyry.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gtbeohugfv.html

[A25] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtrpazplhb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gtfmxqnfww.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gtlkszudij.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtvgsfqlkk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtjgyuyver.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.havefunace.top/Article/details/gteruuhrlv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gthxvhmcjz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gtnzlmwkgi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtllpzavjh.html

[A26] 类型转换总览
来源：http://dali.smart0.xyz/Article/details/gtcsfrgghp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aibaodan.cn/Article/details/gtdvlbjdxg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gtdbetcaon.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gtjtptztsg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yvedp.cn/Article/details/gtmvrrsgqd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yongpay.top/Article/details/gtqkqfxuuq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gtecdttlxj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gtyrisweaz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtvwumupti.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtajngfzrz.html

B. 流程控制
来源：http://dali.sxryk.cn/Article/details/gtjdzeuuga.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtingwjawq.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gtpnfsfhza.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfuxpcde.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtshlvhcnq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtfcwjkryo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtyocemscr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtzjxvxeni.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gtyymnoyzc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtmydahfmt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtzeknbp.html

[B02] 多分支 else if / elif
来源：http://dali.tian-w.cn/Article/details/gtiftggbjg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gteirzfipo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtrtlhpuul.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtrcvkhkos.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtjhxfhnji.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtcabppspz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtmhcfqjrg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gtotyjdfcw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtrvxuevud.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gtibsjqpjm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gtearzxuts.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtacifqmue.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gthpwahzlf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtopoyosol.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtuerzhgok.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtrrxfdxsw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtbobqasyc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtwygfsipt.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtjmxoieqa.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtsplybiju.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtleelykjo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtkftrnpbp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtulizavyb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtbvevtgjm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gtojjnpoqa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtgnvndsuf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gtzsubpzch.html

[B05] 遍历数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtbaluvoaz.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbjhyabm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtamgucapw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcpdaebje.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gtgrbcsezr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtzexztqqt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtlvjcypco.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gttasdtdvn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtwduiulem.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxinkj.top/Article/details/gtvzyoayqe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtpxyopdjt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gtyyxvhhtn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtgmxvfrej.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtkjgtmgbw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyzorjjc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtsosshflb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtfwnzmrwi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shzxlz.cn/Article/details/gtqdijayiy.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtofyrdnym.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtbckcpiqz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtaxqugunt.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtsscmjymg.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtsipzzshy.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtsclgpffs.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gtiznltgtj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtmineplsb.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrpaosge.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gtuehdnjbw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtjgswafee.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtfsrfbhtr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtthcinfrg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtuqvpdzsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtkprnhnrp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtlqlsnywf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyzbsrxe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtcycdqsxb.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gtdtiuyfdx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gtmxsbjbpw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtmoyfvgne.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtarpihzzs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtczflnskd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtpynnbuyk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gtaxvbyegq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gtuclernse.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtrfcgoctp.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtzlksqcxc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgufenzy.top/Article/details/gtoppckpdc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gtkbndwoct.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvafuozl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtpukbbmwx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtuuuatjak.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gtkfymwdle.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtpvwjlnfd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gteigagxxy.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gtfohdhzgi.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbyuxzcu.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtudikhrqo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtujlxjzoc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtchlheuxk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gthwzxufvg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tianlin.xyz/Article/details/gtnoatdezn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtvygfmuot.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttuirjssw.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtbzykijio.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gthsntmkgx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtkoxeiogd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtgeeyolqr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gttqdhrawz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtjssiplip.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtddecbhku.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtprmxbagk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtixunrbud.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtexxhvnhc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gttrpegbga.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtdrqqsvbm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtklmqsfmb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtdfoljnxr.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtzofhnuiu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtvvtiwdfc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtaokrfgsa.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gttpgwjvhn.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtikjxwxiu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtgsthqlpy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtpjzgfosb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfyuutpij.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtjfbbauen.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtvvwofaam.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtkiuxiipd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gthxbpchqm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtngqtfnqh.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtcyppkvqh.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtqqaoqgsl.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtjnwcqhgq.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gttctfhprs.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtlmhdnklj.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtilezlxox.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gttubroywp.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtbjeoeqwr.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtgruapfom.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtqijjtpct.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtjhtweitx.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtqthmwiwn.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtmoorrgtf.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtufjgrtue.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtfbsfwlxd.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gttydrgcuw.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtwfggupsy.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtrrtavpcc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbxrtjkvq.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtmtzbzyfj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjlmzpwpu.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtrpkgieys.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtkcxlxtvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtouziikup.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtemtpgrjs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gthjvivifs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtbhuqgurl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gtuenwjvof.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtqmdnfrox.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gttsjxuygy.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvcgtqye.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtbkgbgaqm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gthqtmecic.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtmlicgaay.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtociqewkd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtftddgwlk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtbiybsfta.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtclsnbyax.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtcowmolsd.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gtdhvxickq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtjyqufvzc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtrzjwozlq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtzzgdhxso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtvguezbbl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtgwwdvnlh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gtytqnbvns.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtzgrzayga.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbsdthuy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtgjhecgmx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gtljtnfjvs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtptjamctk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrokikolu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtqydczibq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmivgtmoh.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtxkamsoqi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwdcxszso.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtvsujygzc.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtenchrjpx.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtqdiwlmpz.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gtvjucxolz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtvtiwnihh.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtbztclqvx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gthiwjlyjw.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtaeyuhayq.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gtfglomcmd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtzasjdaoa.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtejueeqrp.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtbgyssnaq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtkvxoncqa.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtqaqievat.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gtwpkmecxc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtvfupavhh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtqyeljjfo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtvcjvyckz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gttlazpvsu.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gtronveqfd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtjagxyqid.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtedxqxwpp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtnbihqftz.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtgjfbnzgv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtluosxjce.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtbnitfxrn.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtgryaqqli.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtsqlztksh.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gtmcirwclc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtmyeqirfh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtrgbtushy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtoxhlhetc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtoxgmkukk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtdvczukds.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtdnvzgpur.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtxldeywty.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtbkamxqqb.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gthygkdrse.html


<!-- 参考信息 -->