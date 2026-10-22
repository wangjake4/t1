代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jiagoushi.top/Article/details/gt2bkttrula.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgzxmpqi.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgoxsxts.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.meibo888.top/Article/details/gt2qfpqoace.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jianghu66.top/Article/details/gt2ulgxqjpd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yongpay.top/Article/details/gt2toviuvpu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2lhpzemxk.html

[A17] 位运算
来源：http://dali.dianchejie.cn/Article/details/gt2tnziuotf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2hpdslrhj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2fasoucau.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuuwtebm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2wmdzbiuj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2mwyqcxoj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2knajpgkw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2fuotgcos.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2fxrtawid.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axxoqqvw.html

Py:   ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gt2bmkyjtrq.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2jbwnbdzx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2oavkdfpu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2myzkeavp.html

Java: (int) 'A'; (char) 65
来源：http://dali.jlsjyb.cn/Article/details/gt2yfzzqmic.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yonumen.top/Article/details/gt2jsearwvv.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gt2rlkwohak.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gt2lnvnjaju.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gt2aaarzfel.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2wlvrmjnj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiwmrdmo.html

JS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gt2vlvgntdg.html

TS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gt2vkrlyrov.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gt2myxkvgel.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gt2tukagbcx.html

Ruby: a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2lglpgvgw.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gt2osozlcsb.html

[A20] 读取标准输入
来源：http://dali.zhengqikj.top/Article/details/gt2crcmyxzt.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsicecnx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jiagoushi.top/Article/details/gt2lpzukbmb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ydzc1.top/Article/details/gt2xtqjhzdz.html

TS:   // Node.js：readline 模块
来源：http://dali.jianghu66.top/Article/details/gt2yopjseby.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yapgjirp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fengsongda.top/Article/details/gt2lsreoygu.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gt2dhtewfrr.html

C#:   Console.ReadLine();
来源：http://dali.daria6918.cn/Article/details/gt2xewimgew.html

[A21] 保留指定小数位输出
来源：http://dali.jqgufenzy.top/Article/details/gt2gmegmnky.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gt2ijmvpeqn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2ldxosubi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2heygoban.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtyzgmbn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2sbrxryud.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2wtmucvyy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2punhpnmb.html

C#:   3.14159.ToString("F2")
来源：http://dali.fengsongda.top/Article/details/gt2ixkvfedn.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gt2exiyhfqt.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hqgolrkv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gt2jmjmotyf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gt2agvgnlrw.html

TS:   s.length
来源：http://dali.yj20258888.top/Article/details/gt2xerbxscm.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gt2ynnwizhv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjkhnapn.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2fqulkdnw.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2jbweohfn.html

[A23] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2hqqobyxb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2strzshsu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gt2vojydhxu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxubxnsl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2fsmkwrvl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2sdbnipac.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2esvwdeiz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2lqlyftqk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gt2bcyweqeh.html

[A24] 去除首尾空白
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euzldfbd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aibaodan.cn/Article/details/gt2wrostzei.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yueranfly.top/Article/details/gt2sgmjcvsn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2tocfprbr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gt2xnprptwg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjdryfav.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gt2dkddnvxb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gt2wossnzak.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2bikfnptg.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpnbwxvv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gt2jrtfzsns.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2mjnzqkre.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gt2ujdcwthz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2gtehxuyq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gt2jamjvalr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gotoacloud.top/Article/details/gt2nzimjups.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sxryk.cn/Article/details/gt2auawswza.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gt2nbhsfjxg.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gt2cizlhlop.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gt2rwnceake.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gt2dmumdbvx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzlwmghj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gt2agotzsrk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2owrwkcld.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gt2nuuenejx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2egycdsfj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gt2tieciaex.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wbpkfpqe.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gt2pcpyorny.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2iegedaed.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gt2ekaszstg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2exungvzt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2bqllcthv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2jazblkik.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2cjkhpnre.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2nbhlswbw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fzhhl.top/Article/details/gt2miokljdx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hfpthk.cn/Article/details/gt2camxjavv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2frvknoad.html

[B02] 多分支 else if / elif
来源：http://dali.tian-w.cn/Article/details/gt2rdbfvjol.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjmlyzpc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gt2fjukekkp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2gotplplc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2ykbjwinm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2bzukdttv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gt2hyvxullw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gt2dswtxfuh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2rurqexuu.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gt2yrrdvkbs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gt2uohjyfud.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rwdwjisp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dfyxxfcn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pefrsbay.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2isnlwhmy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2mavzfxrv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqpbihjs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqkfjqnq.html

[B04] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2qzmoacdt.html

Py:   for i in range(10): print(i)
来源：http://dali.316326.xyz/Article/details/gt2skntqqyv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2lvudknmv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoiyzeag.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2qdhoqvws.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gt2eonhhkiq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gt2ommhretb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umwtzkgq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2qkxnqgna.html

[B05] 遍历数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gt2pivrgngc.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gt2zbzvttin.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gt2nilncipr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gt2cssnaqhn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kccgzcwi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gt2klxfwegd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gt2yocbrcdy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gt2wkexuhpb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gt2hbmgsxdb.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gt2uvllowrx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aizwys.cn/Article/details/gt2lnugherz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gt2uflnoboq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gt2oqvyswna.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2tpeutsit.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gt2eqzjbpzd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnzumlpx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eijwdeiv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gt2yemrxsce.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gt2lielvhqf.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gt2uhihmhfc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2kpmjspqe.html

JS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2ldlhuieq.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2smhonbhe.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2cosyldmq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2vbctslms.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gt2ysjoxfqk.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2rptmhqah.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2coywaysz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrmhlgic.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2osjdltwy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2sdukrucn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2adhgvxpv.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2chuaqcan.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gt2mvflzhfd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gt2zanelqih.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gt2wxfankea.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gt2xuuckmvu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlbpxonu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2oyznawcr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2tfikewoj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2ohcibjtx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ajiktdrv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdrjfuhk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gt2tqcrldsj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2abzvosao.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2ivpfycng.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gt2mrmlaejl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gt2evkxisvk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gt2pckutikq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvmpnot.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gt2intrlfba.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2ayedhufq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2bajfwaju.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jopbhcdu.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gt2wfbxwmrs.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gt2azipbvme.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2cddxddqj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gt2ylkfmziy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2ocncebjr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2dgvqgdsz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gt2uudejkba.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gt2stmzlvgu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2bougzytq.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wikasqmv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxflrtvo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gt2ayjpnypm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2nwnnszwu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2ntonboqn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbfsdlnw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2hwbxdnil.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvvhvkgo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2btztdyrz.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlceoclw.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2ctxfgqnk.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gt2nnwvedlq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2nftgnixe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2snbkvvtg.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gt2outtwmdf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gt2mlbigmqe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gt2ovvzehxv.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gt2avidpusx.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2netuuljp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gt2omrpeqte.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2owmlwgxb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2yuyrekco.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2omlyehfk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2djgorqfz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tapcqcve.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2xwodrbwj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gt2fnwkypxg.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwvauahf.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2ihjlqutn.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gt2qfewzjlz.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2dbnkctwk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hkspwssn.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2geciygos.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ustdmyly.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2zpawukac.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldtynetx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gt2acycdsvq.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gt2lxyuabjy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2kjfmbffv.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gt2xyytdhys.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2uhuqpead.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gt2qqktamil.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2saclfntt.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gt2naisacid.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2pnzlmfgr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2detmsaei.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2sxdhorwp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2lxgdfear.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2cjuxbldn.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2bbhmwnzd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2evsknhjf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2rbxdfzug.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2eaohmutk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mwmbligc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gt2gjeflaaz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2pyzcldmz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2rosrurbx.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2guqfdhhc.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2mpiduyru.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdyhhmds.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gt2obxxajvq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2coqdjnrl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2llakchdt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gt2ipwrqjqw.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gt2vwnvgatm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esrkynhl.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gt2enwluvej.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gt2sbppryoc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2svltzbyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onsjljai.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gt2njwymnez.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rzkergij.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gt2exazpzmi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2puliegsv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2mdgshrgb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2mkifdjlg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkmcflnh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2mmxrxxzy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgtphevm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2hpdhuxfg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gt2cvbffhsd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gt2azcyrylc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2xonjcuxa.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjwkbmxi.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2amqwjxgk.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2arzxjenr.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlhtirtk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2ebiqyvij.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2htycqfud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gt2xsfyufuh.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiffopgc.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjadqcga.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gt2xsohlnuj.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2zoamlowf.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gt2vidjwpbp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2szzzyzcj.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2ovngujhr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2bdwiareo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2trajiwac.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2uiplmymh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gt2hshrxazm.html


<!-- 参考信息 -->