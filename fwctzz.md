代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.ybcxt.top/Article/details/gt2hrdkqhrj.html

Py:   ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehynpjhs.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gt2oduljlqy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gt2jlxwbmay.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gt2tizdmuzz.html

Java: (int) 'A'; (char) 65
来源：http://dali.cqqwz.cn/Article/details/gt2xobisjay.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuanzhike.top/Article/details/gt2yvhaygvj.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gt2htxgqqtt.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggoifxfo.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gt2zohncctd.html

Py:   a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gt2spexkfwd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhiwuduotai.top/Article/details/gt2eledkxxh.html

JS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gt2zauuzenp.html

TS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2vflqawsa.html

Java: int t = a; a = b; b = t;
来源：http://dali.0kj1m.cn/Article/details/gt2fhbrcocr.html

Go:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2sugusust.html

Ruby: a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzfnskke.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2cfdipsid.html

[A20] 读取标准输入
来源：http://dali.guannengcc.top/Article/details/gt2hxyhypiz.html

Py:   name = input("请输入：")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vipgemsk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubptyhvu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2larmhidg.html

TS:   // Node.js：readline 模块
来源：http://dali.sweek.top/Article/details/gt2mwcnqgvl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gt2swjaavfm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhixingplan.top/Article/details/gt2anfiyahi.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gt2spmtufyu.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gt2xzaxwugm.html

[A21] 保留指定小数位输出
来源：http://dali.0kj1m.cn/Article/details/gt2aokiydse.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gt2rrotxouf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2rdqqquyn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zvcnlqgn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2otehsnwj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2ioojpxze.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2ythccirm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2hyzmnvdd.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhongyouzk.top/Article/details/gt2guwgkfkf.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2qokreova.html

Py:   len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wabknmsl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ydzc1.top/Article/details/gt2yxizubyr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gt2tnoizent.html

TS:   s.length
来源：http://dali.ivvv.top/Article/details/gt2sqeawund.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gt2gshhnunq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gt2bfcjbnzs.html

Ruby: s.length
来源：http://dali.jianghu66.top/Article/details/gt2ygovtynp.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gt2uzmndccl.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2queizzgk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2fpaxvlav.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gogol.net.cn/Article/details/gt2gvdwkhch.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2ougmccwi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gt2yjuopdcg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2sbxozbbp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmwoonik.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2iwbbgxhn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jiagoushi.top/Article/details/gt2tmkpmkek.html

[A24] 去除首尾空白
来源：http://dali.9152youxi.cn/Article/details/gt2bueyjram.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.redwolf501.top/Article/details/gt2dpmkwcax.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gt2kxwakyfj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2abrljixk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gt2fpphgxwl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258888.top/Article/details/gt2kvsusibd.html

Go:   strings.TrimSpace(s)
来源：http://dali.andypj.xyz/Article/details/gt2oliqufec.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cheryme.top/Article/details/gt2ntkxfski.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2wiaughfb.html

[A25] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2uhsqatnn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2knaymvky.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenlongwang.top/Article/details/gt2aryulrhp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2plmsahow.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2ukoplnar.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2fjqmngoa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gt2labbemrt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gt2asokffbt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fayhlmdm.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gt2qnkukevy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gt2arkjpfec.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gt2dvwuujvf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gt2gyparsbh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gt2iwbbwlec.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gt2bulporfl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gt2wxkymbzs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2dvbakwaa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2cbnjzeoi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hzcejswp.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gt2pkzhtumd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxppqrfn.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gt2sqnvepku.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2wtroqkrb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfkbgenj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2wxoqppey.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2sshqgvib.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmbiapt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2txexveve.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gt2rolwlryl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2nuxrhyhk.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gt2lpsnarxn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gt2tjmgesah.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajfqprav.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2racodbku.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2vxxfymhz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2dqmikhce.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hysaishi.cn/Article/details/gt2qcczughz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gt2xmgtskid.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2ndtforrm.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gt2oyfpfwcs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.kuanghao11.cn/Article/details/gt2zmuavsmv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2hcpcncqv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2vvwyipfv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2jgvxcmog.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2iukgmfwa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gt2hucsqczf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxuanxn.top/Article/details/gt2pztpxexb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gt2turfaqpc.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2wwdwuabn.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eysfqbzz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rieardfz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2uoadtgjg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2ijktvgrg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2oyfttyxq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gt2hjyrgeeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gt2vhgnxpaf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2porhwgla.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2glsyoiit.html

Py:   for item in arr: print(item)
来源：http://dali.snrcjt.cn/Article/details/gt2vtrwdsbh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aslopiwh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gt2qfuisdii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2rrxwbciw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gt2qhfwjaai.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gt2ocqqsyei.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gt2mwtijkzy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gt2xgbshgdw.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gt2zlyqrfvk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gt2afcktatl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gt2umkeumtw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2lrqqeiyq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2dazalxgn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ehwqpu.com/Article/details/gt2ilbfrdir.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.svipenyu.cn/Article/details/gt2uyreruso.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gt2mvvdashs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gt2khdvhydg.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmvsznjl.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmkgkkxc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2iatqelvl.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2elwkvqgs.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2qnogfvlz.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2qyrvizje.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tian-w.cn/Article/details/gt2dvdswklo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gt2vhyaafli.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2yrbcifir.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gt2niwabzqp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gt2zkpjzxii.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugcknakr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2sryjjdzj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbnzhcff.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2mdfpqtph.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2edpshfkb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gt2utyubusv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2uqqouses.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gt2ibmffera.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gt2pvvxkbea.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2zdtfakea.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2moxwupdf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2ledgvaao.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2smqijgwk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gt2xjzujtae.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gt2znesubsi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2wejonllw.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gt2uiagyrob.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gt2cnhlzbbt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gt2wtqucfvt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2wkokyuwo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvzticxs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpipoxps.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gt2buwedmgd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gt2uztxthak.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gt2pwbkgfet.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gt2hbhxrbni.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqfyfnga.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gt2wqowtykd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2bynracmr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2cjgkards.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2qnqyskpf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gt2javrbxpx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gt2qtkymwbt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2vwlzygaf.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gt2clvagdbq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gt2thhyfypf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2zymyjwaj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2hvqlwzgq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2ivgdspog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2raqcekhf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2etqeoaaw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpxztmgi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idqgvuvx.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gt2rfyizptx.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gt2eoelfycj.html

PHP:  is_numeric($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aenmlrpn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qojlkfod.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2cdowyhws.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gt2djpxcolt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gt2vmaisudv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gt2hszxbdot.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gt2yknruzjh.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gt2spnbucpd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gt2seyctdwq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gt2cntmdkpe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ilklfmer.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2rlkmgsqq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmnnugva.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gt2emkgysri.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2yrswaahx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qlguzuyj.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gt2zbdpbpgy.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2yynnjdnz.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gt2veowhiwb.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2cglqvasz.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2hsvmxtfp.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2ipyluihi.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2zrovvyky.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2sadlmiwk.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2fkbqykhi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2nvgsphnq.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gt2nrzjlqpt.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gt2rutdlpvv.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqlqygri.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2cmnsgbmt.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2alpcjqxr.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gt2hbegjngi.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2rpllxxbu.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2nhzofduw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwgiwvhv.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gt2ntftrarq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2puqdmxcu.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2sqaptytm.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2drqjthgf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2lktlpdwf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2ffritrhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dwfhyeew.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rndapfyb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gt2fxmqpnmp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gt2qlbyrpki.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2kicvumwi.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdbvvacg.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gt2hcbafouy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gt2gpbrglik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2rpmfjuny.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2gekqlzxq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gt2eenqdnim.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gt2vermnyvg.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2sukbtzll.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gt2cgcgymhd.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gt2ixpacuxv.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gt2zqpdhopa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gt2trmrdpwy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2icqfxmed.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbbfqyjf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ncfsyyiw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gt2badkpovg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gt2inmnqytj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2sqjpqvhc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gt2mjxehfcr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gt2nbvgtkig.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnbwhuax.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2ilrrrwnw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2cwzcngbh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gt2zxpxzqsu.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gt2zairvxrk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xehubkrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2bqfjtrtt.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gt2hqpsuvsi.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvuwjkle.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2nfulbisn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2yjeonzhm.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onzyiuqw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gt2pnjdmeak.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2gihhwjwt.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzqjbrme.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2bhucehfr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwiqhibm.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gt2bjiyiqmx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gt2emmpbvef.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cftedboo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gt2jhctrayq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2dwocbdae.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2erkzfpun.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2wirlejxr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2otbgwnds.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szpgtrzz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2dxmmowqt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jqsgndfi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gt2qyfnygoj.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2ermoktww.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ogwhyfid.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2tcdluans.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gt2etovrtty.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2nkklstzn.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2oazuietu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2hionoers.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2wvbwuvxm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2lqqgxmud.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2anhbcfzg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2jkvtalff.html


<!-- 参考信息 -->