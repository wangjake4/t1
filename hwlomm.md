代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.cqqwz.cn/Article/details/gt2ltkvbphh.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gt2llnughhu.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gt2yczbkywu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xinyue.icu/Article/details/gt2yckeqbew.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.havefunace.top/Article/details/gt2ulepctdx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gt2hfjwnjfp.html

TS:   if (!x) {}
来源：http://dali.shzxlz.cn/Article/details/gt2kubutqbo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2sjbowynt.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gotoacloud.top/Article/details/gt2aunvgfbp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pycfn.com/Article/details/gt2fpucneix.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ouihfuha.html

[A17] 位运算
来源：http://dali.ivvv.top/Article/details/gt2oocdzmqs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdrkcuir.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2yfgobxxe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2oabnmajt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2isbdknag.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvlrqacu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2gnlcqupc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2mbfhmezr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdmrhkxv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gt2aqrsiicu.html

Py:   ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gt2lneitrie.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gt2uhenqdhz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2dxidetji.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjwmeoni.html

Java: (int) 'A'; (char) 65
来源：http://dali.c1oappe.top/Article/details/gt2qwwstmri.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnofkukk.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenlongwang.top/Article/details/gt2fbkmhrom.html

C#:   (int)'A'; (char)65
来源：http://dali.nwbrower.top/Article/details/gt2lsqmphbw.html

[A19] 交换两个变量
来源：http://dali.zhoulong.xyz/Article/details/gt2kcmdlgsj.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2tcdwezmm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gt2ouktndmc.html

JS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gt2mnckugwo.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2qbdyaors.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gt2fshsugep.html

Go:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gt2cxolkxri.html

Ruby: a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gt2xtbofpsx.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gt2ebcirfqo.html

[A20] 读取标准输入
来源：http://dali.bjfxy.top/Article/details/gt2vprpwfqk.html

Py:   name = input("请输入：")
来源：http://dali.ybcxt.top/Article/details/gt2vtymekrn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjygkjsv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqgqlfob.html

TS:   // Node.js：readline 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkculste.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigufen.top/Article/details/gt2apsemxep.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gt2qiqphmce.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gt2fgybadqz.html

C#:   Console.ReadLine();
来源：http://dali.fzhhl.top/Article/details/gt2ppzxqufc.html

[A21] 保留指定小数位输出
来源：http://dali.wangdashe.top/Article/details/gt2mnuruwwl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gt2jtpyspqi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gt2kayfpqvz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpynuuhv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqpvhmlh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gt2acanviyt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2htelchsi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gt2wwgzkrpi.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiuwjadw.html

[A22] 获取字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2dbkvwdqd.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hvkordcm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhengqikj.top/Article/details/gt2ppzzwmot.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xujjbvvw.html

TS:   s.length
来源：http://dali.gzhubu.top/Article/details/gt2mlpyuevz.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2xmyfxtdy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sweek.top/Article/details/gt2ufpmuodm.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gt2ronopfmn.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gt2caijkbvm.html

[A23] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2ldyksfox.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhixingplan.top/Article/details/gt2jiiepxzi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gt2ymgvtzqi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2idnawmpd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2ggrtenhv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2fcbtpfjx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yueranfly.top/Article/details/gt2ecmmscyy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gt2inqcyoun.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gt2gmmbuchy.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gt2ovkflmhr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gt2trqwfrvh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gt2ftsaseve.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gt2czrtkznd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2uisvinhs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgufenzy.top/Article/details/gt2pvybeazo.html

Go:   strings.TrimSpace(s)
来源：http://dali.aibaodan.cn/Article/details/gt2edoamnma.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gt2tpxtnhtt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gt2lpdqskpj.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2evbrkmep.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gt2ejeubijp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gt2qmuinyva.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gt2qibsjxsv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gt2cptyuieu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guannengcc.top/Article/details/gt2cotngoad.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2chwtclbd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yongpay.top/Article/details/gt2slbcjggw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gt2awlgegyy.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykxkhcfj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gt2evyejhap.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.0kj1m.cn/Article/details/gt2bxporvou.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gt2ufvvlgel.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yangfankeji.com/Article/details/gt2dggwyicb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gt2prdhiyjr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gt2zrbrlelz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gt2uudmjbsn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpwmnnwt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xkvrqjlm.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gt2qrgknrya.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcqmedco.html

[B01] 条件判断 if / else
来源：http://dali.hongshengwenyu.top/Article/details/gt2flajlhxg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibfnhvgu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ellrtxun.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkhgenil.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2pdelqois.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2oaihvbjr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iivdjeps.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gt2nshpelmx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2ivgyrjyw.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gt2klfvpose.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gt2rwhxowbo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gt2lovdunyf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2xhlxvwle.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2bhkjrnnh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2hhfawgpm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gt2xqzhbrqa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gt2kdzowgsl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2limikpfq.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gt2ygehgdiw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2xlcpicmd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2xsgoxole.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2sjzhpkhi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2yhfzfwji.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2einlxksb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dynfdnxs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gt2jpmkzfts.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2liqcqoat.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2bmjecbgw.html

Py:   for i in range(10): print(i)
来源：http://dali.ppjwa.cn/Article/details/gt2axsdrwle.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gt2fygivjzx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gt2akeinien.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjnibmwt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gt2qtsixpbm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gt2cirgngyz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.snrcjt.cn/Article/details/gt2gfetqsfl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tjnmfkqw.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2eblawwfp.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gt2ebifpwtz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gt2bdeyqbqc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mphohclr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2copkftiq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gt2zojhizfs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrjzliqn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gt2nydbypfk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2axwuidnl.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gt2emubucpu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cheryme.top/Article/details/gt2ycdjodhx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gt2eelbktjn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsoyuvux.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2hvtnfzuv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umnymwmt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gt2fvbsyjex.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gt2peszqdux.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gt2pmfxsirv.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gt2kwayjitx.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gt2whzuacxs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gt2zwspzfce.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2cioqftvp.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdyfoeog.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ygaopkby.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2nvkhpigz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gt2hdopamjz.html

C#:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2nxacffhd.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gt2ykwtqipi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gt2aonbjtkp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2cyczhlgf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2xleyzobt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2fcxjlrlw.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2oayupcyp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2igxclckn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2glgvnzjl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2leboemrs.html

[B09] break 与 continue
来源：http://dali.ehwqpu.com/Article/details/gt2tvlzlvfh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgeskleb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2cjbzersa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2ucpdzyzg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2rvhymhhk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2lgzcnuwt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2bfwqyjfo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hammf.cn/Article/details/gt2xnqwrtwl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2uvimkvoc.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2gxkizhii.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gt2nlnatshg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2zznjzslg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gt2rbdsygcq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gt2prgrmzfw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gt2bqejevgp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gt2himxbmxy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gt2obngrqqx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2tnslulsb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gt2atqvhphc.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2xkpuwscv.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2oxrhegff.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gt2vkqospti.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2eamtfyke.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sppaxdcb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gt2qapdgysq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gt2skhuuulr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gt2cbaewnbx.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2hcsrsnni.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plxfkfig.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gt2glozlteo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2hsibplcu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2xhlvupde.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2axlyzaoo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khwchydc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2krdhfusy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gt2dzazekcg.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gt2jzuvtiku.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpzgzvoy.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gt2pketorqx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2hmmgzgtn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrxdevuh.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaohensa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gt2tlqdgdbv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2vygslore.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gt2nultxupr.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gt2ghdawbsi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihtaucwu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adqowske.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kntomutx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ndczcciq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nyhevpdp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2iysejblq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbqwzk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdohdyca.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gt2vtcsnieo.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gt2peoyuauj.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gt2xisipggz.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2aczqsivr.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2eqktcxoi.html

Java: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2hvnpngvm.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2wadsfucm.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2lgspepuk.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2dhqsxtoy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2qyofmbqo.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gt2dwpbwpcg.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gt2ujztevlc.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2kaswzguj.html

TS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2wgnfxmpr.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2gibzdhta.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gt2oxzlqexv.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gt2eoplaimt.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2cauwbbsr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gbcguhoy.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2uqtdwinv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewciilwq.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2vxejpkqn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2nxhztrks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2sqozawwt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2omvqdkhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2jpdjhutt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2iawwcesm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gt2kpxrulka.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gt2jpdpeyti.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2oulfpafz.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2smywugtu.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gt2xxtbbanu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2clxcwqgc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2ugnurvgy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2jzwnrujv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gt2afpzhmwf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hlebkljt.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gt2kxgitgzz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gt2fosawcaa.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gquqlrst.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2pyxuvtbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kidohops.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2wkpbwfop.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2objxdkrx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcekoyqx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2xtjuwgij.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gt2oirndivr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gt2scopnkib.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qncksyhf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gt2ychaaxtq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2xddpnrnw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2zkinmjii.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urljuqhm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gt2dtrcrgcu.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gt2envyjnql.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2zaucudqw.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2dtqkcnif.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gt2chacikka.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2kdyglnut.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2fofycudm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gt2iofattfo.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2gqowovpy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2kapwqptz.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpbhigum.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gt2qffdwzlw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gt2dvcvxffo.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gt2arzwjdim.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtbfiuhq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2tpekswzl.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2djszomgq.html


<!-- 参考信息 -->