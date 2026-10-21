代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gtwntgqmdg.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtdbcxhrav.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtyyltkbdj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gtiwvddigc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.meibo888.top/Article/details/gtnjfsgqkw.html

Java: (int) 'A'; (char) 65
来源：http://dali.cdnleiting.top/Article/details/gtfllphhjd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gtyhhgxzur.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtjtiiuycz.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtqjnhxass.html

[A19] 交换两个变量
来源：http://dali.fengsongda.top/Article/details/gtifhcpraf.html

Py:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtzsyesibo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenjidiqi.icu/Article/details/gtfcoxteoq.html

JS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtrnxlintm.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtzwzldyin.html

Java: int t = a; a = b; b = t;
来源：http://dali.sweek.top/Article/details/gtekvjeaqc.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtuquzwquu.html

Ruby: a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtdzqbazsw.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtjhufcvws.html

[A20] 读取标准输入
来源：http://dali.nwbrower.top/Article/details/gtmmpwcpkt.html

Py:   name = input("请输入：")
来源：http://dali.pengpengdd.cyou/Article/details/gtdaofxxah.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.meibo888.top/Article/details/gtdberdatc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyiymmmo.html

TS:   // Node.js：readline 模块
来源：http://dali.xylfe.cn/Article/details/gtnxslvkjt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dianchejie.cn/Article/details/gteszxzuhw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.kuanghao11.cn/Article/details/gtcibntfmt.html

Ruby: gets.chomp
来源：http://dali.jlsjyb.cn/Article/details/gtweipswxz.html

C#:   Console.ReadLine();
来源：http://dali.dianchejie.cn/Article/details/gtmfjunvbe.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gtbgefwybr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.316326.xyz/Article/details/gtzpvnhdun.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtihtflvum.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gturjfwhwd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhvfanav.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjezrtzy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtfcnbjxnu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gttefwaxss.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtpieynulr.html

[A22] 获取字符串长度
来源：http://dali.shuidangran.top/Article/details/gtygdtswma.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gtenywdtye.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtnippznum.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtqyiozhny.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtvfauntxn.html

Java: s.length()
来源：http://dali.chenlongwang.top/Article/details/gtbsjiyscw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtryvlkhyr.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gtjdplrkwt.html

C#:   s.Length
来源：http://dali.fzhhl.top/Article/details/gtbtwcmvbc.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtrejxdbkz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjrkbtpa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pengpengdd.cyou/Article/details/gtarlcoyzx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtymfislmf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtcbnamhwk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gtknyntmow.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gtnhnozpxh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj202588.top/Article/details/gtiscjkikq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gtutnlzhai.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gtvmpaxciu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxuanxn.top/Article/details/gtvyyyavck.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzikqjcw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtxuqpmujp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gtxujzyhgg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gtxuegaopm.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gtfgmjjbku.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtsrsiogfw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtftmghiyy.html

[A25] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtacmssdzq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtwrefovnd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtqtukkxxg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtxuuypluc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gtyejqqkfw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtfmqtuyms.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynpmlwxg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gtjqrcjyle.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtvyhiawxv.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipzdgpjt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gtsnulfbyi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwfjhrlg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtmzbpmxbr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtnnkmxbsv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtrerjjslq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gtjjjkrnsq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gtnohpdwir.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yangfankeji.com/Article/details/gtwtuxabub.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlwslolbb.html

B. 流程控制
来源：http://dali.xziqi.cn/Article/details/gtwpmsclhe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtayjxoabm.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtckvqziou.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhengqikj.top/Article/details/gthlwgkzsl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuxhznbhi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtopdxwxyo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtcadatrso.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtaasgytbu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtekmyxvml.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gtqgzfseuw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtjvmchxkl.html

[B02] 多分支 else if / elif
来源：http://dali.ydzc1.top/Article/details/gtanokhhwt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtdedhgvjb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj202588.top/Article/details/gtujvxyfiq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtbhhdfmev.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtsybyudsk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtcxlasxet.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gtyqoeifkd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxrwdwxn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtbjepvwqg.html

[B03] switch / match / case
来源：http://dali.gaohongyu789.top/Article/details/gtjwnlezey.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtglvlehpm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtgpvrijvx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtcbwisskq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtxfztuuqw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtfgmfnefp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtxcewbupu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gtwieoazlt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtqggayohc.html

[B04] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtcjegaglm.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnrfppof.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gttwwbkonv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtstemuitu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtrcknbeuu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtqpbicdxg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gtnuynjtrp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtszefxkts.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.andypj.xyz/Article/details/gtujanxvou.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtjpkhguji.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxshkodu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gtlgeljxqg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gtbuxrcsvf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtpxorkbho.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gtgjhbvyuk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gtroonkocq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gtabenjndh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gthdpjitop.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtxdwpgmbh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gtncaprizq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtwevgedgj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gttuuxynxi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtqqztfwfq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtotgepqdv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtrexirzjh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtwgswsbkv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtkrpwttvv.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtpffsichk.html

Py:   while i < 10: i += 1
来源：http://dali.ehwqpu.com/Article/details/gtfiqvtjsp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gtvnplqpkz.html

JS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgyaxyfc.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtnfspyama.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtjplkryww.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gtddeseuki.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugpoqtvx.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtulnopxhl.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtfdpzqjfj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtywgcogsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtcuhafcql.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtpqtoznzk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtquinjepu.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtzjwrhrhj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtwvwwrxxm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtirmdclto.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtsclcxgak.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gtjftnumxl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtszhocwoy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gturymyalk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtzerzuswj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtmelyyklh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtkgaxwllw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gttnorewvc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtsbqhfsfv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtwgexesbl.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gttkpioiui.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gtjurkenly.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtbnjeoexc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtmislaryp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtcbnezhvf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtrktsjywa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gttzxilfau.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gtlclqgkkq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtnnegruqs.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtukzwipvp.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gtwaujscpw.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtwlvhmjrw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtvqzmtmru.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtalavqeiv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtsymltlxg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtjkcrnsie.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gttdfhvqmb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtisdltyzi.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtqyymxker.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtlemhijgf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvnjsyur.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtnvwzmrtz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtgqgsqonb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtuabchjwo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtwsnnlyjm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gtonflbtlg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gtndnuqunx.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gthgsmiwft.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtbcabcuuj.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtmetizpwv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtomnggqoo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtocfytuay.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtjqgjvyib.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gtwrtzfihv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gthttwnspt.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtdhtrrwej.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gtywgnjkjv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gtqwqmybhh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtuqvbadbk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtgmwwhssw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjkegkwu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtptumnqmx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtyqldujdi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtythdlpuy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gthvafuumu.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtykvpnsya.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gtsxwobgkz.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtkixhlvsh.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtvdgldrsc.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gthspqsuvy.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtmvvapmch.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtqbfvlowa.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtudwqrksu.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpniasnrg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtjrosxdgf.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtufzrycyq.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gtgqafeect.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtrpgkpbve.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtuhavuvck.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gttwgvoxuu.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtvqveyecy.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtcqsquhpz.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gttcckptgk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjqxxlbdb.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gtzsciytvy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfiisbgug.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtwuipxcdj.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtlhvoiqeh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtrtjfwhmk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtptfnelyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtctfaallx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtzoxigrvj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleynrfwx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtxtspsgdm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtgjnhzeup.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtuqdcvkfc.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gthfmvnyey.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtfoicwwcr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtqknbqzuo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtrwlxovxi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtazewbbww.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaphheqqm.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtpbntgzxy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtbpooiisc.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwriagth.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtfodoknqi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtthpauomq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtjskymhfa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtuhqtnnrq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gteixwdfbm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtyagzhlej.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtxxkuqivr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtlfmjxzcy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtlwbrxtdx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtpulonjvr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtuxfwcgbm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtwabipmiv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtoicyrvjk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtzadxqhze.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtebpdqhsh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtmckybari.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtrnwnbyel.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaounsgeg.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtghdffwsm.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtcnzkcjuc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtvcigezkn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtxhqfkifh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtdkldqhfq.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtouleafpp.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtptnrieyo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtvvxrtcxl.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gtfnqusvkn.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtvbpkuksd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtzdhtstxe.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gthlmiarph.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtkeimassg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtmjpbrfxt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtbkxntqrl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtafzwyjdl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtcttyuxaq.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtjsntimve.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtfedtgkzl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtetqcghys.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtiwnyavnw.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtxzfuaxiu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtttxnthpm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwlozgsf.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gtofmkfivv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtcszchgec.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtpdgluvvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gtjmainjkx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gtknufphfo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtztkagrsb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtfktsbhjx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtpddoogmm.html


<!-- 参考信息 -->