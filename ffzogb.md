代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2criginrh.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2pyslswln.html

Py:   value = data or "默认值"
来源：http://dali.xylfe.cn/Article/details/gt2mrcnwirm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2kpryvfmg.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gt2gewsjdpc.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkxzolla.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tanke756.top/Article/details/gt2mumomink.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.9152youxi.cn/Article/details/gt2rxrnznna.html

Ruby: value = data || "默认值"
来源：http://dali.havefunace.top/Article/details/gt2lrhmjylu.html

C#:   var value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2pxdntcij.html

[A16] 真假值判断规则
来源：http://dali.zhongyouzk.top/Article/details/gt2sehfdeog.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gt2ubkidmjc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuetiantiany.cn/Article/details/gt2srokbnuw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gt2abegiadn.html

TS:   if (!x) {}
来源：http://dali.0kj1m.cn/Article/details/gt2srabswep.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2lkaeswhz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfzlybar.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fzhhl.top/Article/details/gt2crpcrvzt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2onsjxskt.html

[A17] 位运算
来源：http://dali.ivvv.top/Article/details/gt2tbxmdqmm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2ibiilszv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2ljkyegxx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2ksdxifwq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2theowxje.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doavbbuv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2wzmvqnmj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2infucbtf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2ldhvsxql.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gt2ahdvcbqw.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2uyrxykkw.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gt2wtofemcj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gt2thpqbumh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gt2ggnwjvis.html

Java: (int) 'A'; (char) 65
来源：http://dali.jlsjyb.cn/Article/details/gt2xiaivdxn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhmjadcx.html

Ruby: "A".ord; 65.chr
来源：http://dali.shangyingyoupin.top/Article/details/gt2wenyrgwr.html

C#:   (int)'A'; (char)65
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffxviify.html

[A19] 交换两个变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohtxszcv.html

Py:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gt2wipjcrbb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyjpxvjb.html

JS:   [a, b] = [b, a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skdonhfk.html

TS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gt2skmpvomk.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gt2xjqoqbnn.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gt2otaouybt.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2fcdueqyl.html

C#:   (a, b) = (b, a);
来源：http://dali.shzxlz.cn/Article/details/gt2ycbqrmam.html

[A20] 读取标准输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlrnuafd.html

Py:   name = input("请输入：")
来源：http://dali.9152youxi.cn/Article/details/gt2xlapgvhc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sweek.top/Article/details/gt2iriwtkbh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuiklibx.html

TS:   // Node.js：readline 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipddkspu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258.top/Article/details/gt2sxeazqlf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dipjasdi.html

Ruby: gets.chomp
来源：http://dali.xinyue.icu/Article/details/gt2vosoikve.html

C#:   Console.ReadLine();
来源：http://dali.jiagoushi.top/Article/details/gt2eioagpgr.html

[A21] 保留指定小数位输出
来源：http://dali.jqgfzy.top/Article/details/gt2miuywhgz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbwsthrr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2clqwizyn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2rjooyetw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2gjuuemfx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gt2edxlgwve.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2zervoblg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gt2abblqdoz.html

C#:   3.14159.ToString("F2")
来源：http://dali.gzhubu.top/Article/details/gt2olmqssxl.html

[A22] 获取字符串长度
来源：http://dali.cashguo.top/Article/details/gt2sklgbzox.html

Py:   len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhtshimq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gt2voxcppch.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pengpengdd.cyou/Article/details/gt2nshbhhpj.html

TS:   s.length
来源：http://dali.redwolf501.top/Article/details/gt2aqgotgfd.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gt2fqmfhwzz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gt2olzwkhxm.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gt2wbqqfrpu.html

C#:   s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2zynxwzqj.html

[A23] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2snddbjem.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj20258888.top/Article/details/gt2feqezhqk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gt2ylicfvrr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2gmkucudz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2aenvqnqz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwjryiff.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yonumen.top/Article/details/gt2vthfdgdi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2bslxbxsa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gt2reltnjri.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gt2brjxhuby.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gt2rbgkvhzx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gt2alppmomm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2puqtkhll.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gt2irpctfqe.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gt2thynnlzq.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gt2exoywuim.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gt2vqrdokbz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2qezfjqpd.html

[A25] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2cnwkeguj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gt2xsuekfxg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2stppwqug.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2njdxrfcm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gt2wquztuec.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rzrvkdwx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2aydbumzc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gt2jurdgsnf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gt2xsnotmvx.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gt2rsvfcqrf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.bjfxy.top/Article/details/gt2kgtqetjv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gt2cqugckpw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gt2tggvtpic.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gt2rvyionqe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gt2xtlukhny.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gt2iymxnhco.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gt2xrqwsdcz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2jxgnhjfr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjbxjqkq.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gt2ojznwtrj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lqdykjqz.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnogeauc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgfzy.top/Article/details/gt2ydgnjxao.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cashguo.top/Article/details/gt2ownckcnf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2oholhveg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2mxymloxz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2ukavwhha.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gt2zvjzrruf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2axbmbhsh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2xikqqill.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gt2haqjrojn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yanxiufei.cn/Article/details/gt2hkwrlqfx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gt2dxfztnwp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2zvrnfrmd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gt2nhtslwvb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2rpgfybra.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gt2cvrfammt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gt2hbqpegkd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2bqzjrzta.html

[B03] switch / match / case
来源：http://dali.ppjwa.cn/Article/details/gt2mqilvtbi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erjkmops.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvqmdmpv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2jkmcihip.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lzlbuapr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2lesiezzl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwfbzmwm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuetiantiany.cn/Article/details/gt2gentpskm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2duwevjcb.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gt2yvvcsmmw.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gt2hgxtirbu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gt2kzdjgoqc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2ayblxfyz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qdacnybk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gt2codtvjdg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gt2iywptrln.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gt2tufjbtwq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gt2plmdihrn.html

[B05] 遍历数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gt2vmdwchfz.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gt2hcoufkxr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gt2dnlnkxdl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2jodccpph.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gt2fbjoevho.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gt2wklbhruf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gt2eauxavlz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gt2kggbluql.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gt2yeapalrv.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gt2mlcogxcj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biwtfizi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gt2tujzubzg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tfrimmnp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2xookotfl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gt2uzkzqynm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gt2fsahgqda.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yangfankeji.com/Article/details/gt2zzydkgxn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2qxfbpfoh.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gt2ymhiqznm.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gt2ntxrtykm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gt2ytexgmkq.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2cvdtamca.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2wmcrqquv.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2genykmqi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gt2jopaaged.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gt2efgbneqt.html

C#:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2banyoocc.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gt2ryivcptu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gt2zdfcfhvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2mjodlfud.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2otrneyut.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfiyvikc.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2cpjgcdlb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2cubdwicz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gt2bfgdipbx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2kwanexkx.html

[B09] break 与 continue
来源：http://dali.mhx1999.top/Article/details/gt2mkjyugyc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gt2vfpxeefs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2qpdlykrx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2gfarxzwh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2agiwauwg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfchwefn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2fkfnhekp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gt2cgpwmckd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uoxkagqq.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfyzbdmy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etksiwcf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gt2gyqblnbb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gt2hmjzwjqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2jkjxyzkc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gt2kpusjvue.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2yvvtdknm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2qvudtzmd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwoobsdv.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gt2afppdzoi.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gt2ttpfgozm.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2rzjpxnkf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2reblliaw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2iiadijam.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gt2zebiqsny.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gt2okuiejbj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gt2vukzvkpo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhvlxwdj.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gt2volktigd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwjvrikf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gt2yvjgbzeu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2nieezlsu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2moiccavj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gt2iftrdqoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2ckfsirrv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gt2gyxazrxn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gt2aafduuhm.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gt2jfzjcfas.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gt2smnbrtlx.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gt2zmavixyd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpgydmge.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gt2kgdhtyir.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gt2lxgofeck.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gt2hvexcnfx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2ykcmsrbb.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2grhdymml.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gt2yacpople.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqclgaul.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gt2onzpbnhu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2iimsccax.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiyzznxb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2syrhjnuf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2gtmoxufk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2qtehpfex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2yzynvarb.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylmkqmeh.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gt2nwngqjya.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2moysszey.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2ummditht.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2vmdmfavi.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2wixzxfby.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2itrjknil.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2bvesaygj.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2dhqdbtil.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2hnhlozly.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2mfkvdnea.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gt2uckjggwy.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsorxljs.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2yyxlqmcb.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2odqpesyv.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gt2fjaqvymb.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qafbpigs.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2nmsvmwdp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hkahwjjd.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvoeyobm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ouafevjm.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsatrdba.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsclhezy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2qtdemowf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2aftdktpn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fcxxbfha.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2pzmlvirm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2koyotehw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gt2olpejifz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2vvndwcbx.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2bbvbzwgs.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gt2whdwfvca.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2ynbhelcd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2eypnzegl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2mdtlrwer.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2ydlwuunx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2ramysxhz.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gt2ozaonwje.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2qrzfaurc.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gt2qvxgswwc.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2hvbpkxxc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gt2ubdalitz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2admlcftw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2yfofqalr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gt2otayheyq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gt2txuxbhaz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gt2cqekdpmj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gt2guxiuaol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvhlzmtd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2ywmfkzfw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2cowkmdjg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2uckflfvh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkuixejm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2dmkctwog.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2bosxflsz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2egjogjlo.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2iymsdnbh.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gt2eovanxvj.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2thtzkrvj.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gt2klizlapb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2tvmthqpc.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2oerckhnr.html


<!-- 参考信息 -->