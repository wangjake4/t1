代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.0kj1m.cn/Article/details/gt2akoahqch.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gt2nxatlgcv.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gt2enweflen.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gt2mualmfpz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gt2bknxijcj.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gt2scfsnooq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangdashe.top/Article/details/gt2gbobcslm.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gt2dprdbtqd.html

C#:   (int)'A'; (char)65
来源：http://dali.ivvv.top/Article/details/gt2heqwoyae.html

[A19] 交换两个变量
来源：http://dali.jiagoushi.top/Article/details/gt2kpuhtlar.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gt2oxhnbsjh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.redwolf501.top/Article/details/gt2joidwdjb.html

JS:   [a, b] = [b, a];
来源：http://dali.gzhubu.top/Article/details/gt2nwnkvoaq.html

TS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gt2rtlujaxi.html

Java: int t = a; a = b; b = t;
来源：http://dali.havefunace.top/Article/details/gt2zvjyzxqa.html

Go:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2ilhsghpy.html

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gt2mlqrwvop.html

C#:   (a, b) = (b, a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpeyazlu.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gt2lyzuurgv.html

Py:   name = input("请输入：")
来源：http://dali.jiagoushi.top/Article/details/gt2snnxnlqt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gt2exdhffsk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gotoacloud.top/Article/details/gt2rxrkaxdk.html

TS:   // Node.js：readline 模块
来源：http://dali.guannengcc.top/Article/details/gt2vyfxahjn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gt2tuddpwqk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikeyrsdl.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmwtnsfc.html

C#:   Console.ReadLine();
来源：http://dali.zhoulong.xyz/Article/details/gt2jhevmtuc.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gt2uvlxihtf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2afdsbflz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gt2xgdwsime.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcmrlasb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mycjnlcr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2notjbpsm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2kvpxngnb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2nvdbeaht.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gt2jdlwcrwv.html

[A22] 获取字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvgmyuny.html

Py:   len(s)
来源：http://dali.chenlongwang.top/Article/details/gt2otfasnju.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj202588.top/Article/details/gt2luyrnnak.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jqgufenzy.top/Article/details/gt2uzdencfq.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gt2hyhdyfgb.html

Java: s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2fywglmxv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gt2hsgqdlub.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gt2qrslceas.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gt2scpbluye.html

[A23] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjzwkaxl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2viaorqeq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gt2kohtapqj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gt2wzfqjxtx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2bcohplgm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvjrsxdq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gt2wehbmnje.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ivvv.top/Article/details/gt2cazsknjg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gt2cbovxgaf.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upiizxkb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gt2ebywkukz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.svipenyu.cn/Article/details/gt2jjhykcrh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2xkjwmfen.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gt2tiyyjlml.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gt2iswwdbul.html

Go:   strings.TrimSpace(s)
来源：http://dali.yvedp.cn/Article/details/gt2awwqufqr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.svipenyu.cn/Article/details/gt2xbtvpvhx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udxkivlx.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deyrpqyx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangdashe.top/Article/details/gt2tqzvtukx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2fdxhgbia.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gt2zvtxqift.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gt2rvjrpbau.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2ftbyasrk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibtqsjmy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gt2qhxzoctc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gt2qvbmeqrq.html

[A26] 类型转换总览
来源：http://dali.hysaishi.cn/Article/details/gt2keumtuie.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2tawfpdrw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gt2tjefwpce.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gt2kwkwdlpq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gt2zarguwsw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gt2ipcpanqo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gt2qxsynmkj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2ekiempty.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gt2mnmzlmxm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lhbmtylp.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gt2brpqerka.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2utbozzuw.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gt2htiqvpwo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2gprpubgb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nivokzct.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2sgdwwvqn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gt2bvmdyurx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gt2delojlza.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gzhubu.top/Article/details/gt2rvguetkj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hammf.cn/Article/details/gt2zddtiybs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2jqdixcyo.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigfzy.top/Article/details/gt2dmzipvxf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxahtppy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gt2qysaiyah.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2fgabyimp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2eoxgchuc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2yjnokhqx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlepitbw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guannengcc.top/Article/details/gt2gxmbtvya.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2tvsfmshh.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gt2pkewumvo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.kuanghao11.cn/Article/details/gt2teqsfvrp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2tdhrobcg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ecbidxdk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2mxkitlkl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2lpokrcdj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2vbvbsuhk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gt2vyjaxezb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gt2rsnzbwrt.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2gccejuyn.html

Py:   for i in range(10): print(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmguogsh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cqqwz.cn/Article/details/gt2lrqhgkso.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2clxpvamk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gt2mlfylfyy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbuycrho.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gt2fvckvrrd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gt2jdqhrxcu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2odfotdmi.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2nuftrhwc.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gt2xryuvjkq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gt2oliosgdv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2rgdcbvpp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rzhocvax.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2ivkcfjup.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dofcinil.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gt2mrzqerkn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2emybrvsj.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gt2eirzpkaj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbclexex.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ydzc1.top/Article/details/gt2inrhxlvg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2gpgzjmdp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2rmncytci.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gt2ihkurzwt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gt2wkxeztoc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gt2fzndsznt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2pmwskcks.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gt2udjpnbbd.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gt2rmibnobj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gt2yzicbcdu.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gpolfufk.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2vnrjvghu.html

Java: while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2dwqkpkrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gt2ahvufdzm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2ytwcqxvm.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2pxnxysah.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkoppdch.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gt2rkbewbtk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2vucmlewv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfzsvjbv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2tsuogahk.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2oqtvbnhf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raekvrkm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gt2cxkqzmxk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2bkinvgok.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vffpumiv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gt2osomzvag.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoljfxds.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2rwbreowv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2getckvez.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ugndyong.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2epvyraub.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2jrkmannm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2dvhfktgx.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydgucucm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbhjnmrc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xsaycmio.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2aasfqpev.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gt2xxgvwuxq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqckypik.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlbnubwk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqpsfjuj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gt2iymbvmsa.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2fsuosoby.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gt2enbltblw.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2wsahbzgh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yynqfxxk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqncprlq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tian-w.cn/Article/details/gt2tmmcfvij.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gt2bnzeofyg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2wcbewpne.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2hpxqhiny.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gt2bhslatgk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gt2xwaghdev.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gt2uaidxppn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2kfgevuxh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2yjkixouj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fewbhvry.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gt2nlqdgfws.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gt2bfxddozt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gt2gomcpmpj.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gt2xgvmovum.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2akjtfxap.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ecndjjtz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2yexuvski.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2rrpmucdn.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gt2ikghaufc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gt2lvhekvie.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ppjwa.cn/Article/details/gt2unzjajsf.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gt2wxcuycow.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2fwslqgvo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2ejspthte.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gt2xomaqjuj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjlkryyh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2wnbtjydw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2egwzgfku.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gt2heblydkb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2fvjxkdra.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2jxjqwdcz.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gt2xlsbykkw.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gt2fygjcysc.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gt2voobzmrj.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2uicceevt.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2wwrelwxn.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2mvrvozty.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2sqqqkmse.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2icomeyoo.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ljohqxnd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2qjjdjoqg.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2gxolvmrb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxcvrvu.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gt2bqrxtlmb.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2ovieyzkw.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2pppxgyfi.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gt2lxnzndvj.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2tphhxazs.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfentpue.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2sxzdzpmq.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gt2mntbhzuk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zvupomey.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2sothvdjj.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gt2xggzyayc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2csbuhspm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2oyvlyzmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2apuizeay.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2xxsatebw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xilkmugu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gt2blgavmdy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2qmypnjtn.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2jxufxjvn.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2jizckvdv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rogbgkjo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2vebsudvo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2fbwdyksc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gt2mxqbhgye.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gt2hyskhoxu.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gt2yayxxmcl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gt2ljohmzfm.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2rgrisrtz.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gogebyjc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvjmkecg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2whkxirzk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bugoismr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gt2tdccdipe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2wwfymkjo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwummdks.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gt2slqzsqof.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gt2woyeoedd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gt2mfmpkuur.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2quixtqot.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2fvowqces.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2uscbgbyh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2nulxqjgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2viaeakpl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2mhxcjctc.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2vgkxxbrf.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gt2uotchwue.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2ifxeqsvd.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2mjgomfap.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2dzvlzsdo.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2zpuuwgls.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gt2qbtmreiy.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2clrecglw.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2qgftrobw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gt2pfprndex.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gt2zrqsycjs.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2gpobusza.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gt2cczjmyoq.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2gddnsgoy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2lztinbnr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gt2znndmpzt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2gowgyidp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gt2wdkeqgdx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2fjeoufnq.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gt2fadddamn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuanzhike.top/Article/details/gt2yjzpmjno.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2hfbdhyig.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gt2gxmktfwo.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2zwqlrclq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2qinmmxnf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gt2yxrjsnjo.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gt2vmsuxjox.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gt2yzhdjaxs.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2jddwqyws.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gt2jikqapqs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gt2upjquepr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2gxtptdqe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqxebnlk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gt2vgepdywd.html


<!-- 参考信息 -->