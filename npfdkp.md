代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gt2khgbllcp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yangfankeji.com/Article/details/gt2lecprzvo.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctetinfe.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zycfv.cn/Article/details/gt2zxtqkeyw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.havefunace.top/Article/details/gt2sphavkov.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2jzsklivm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.meibo888.top/Article/details/gt2pvhsqiwq.html

[A17] 位运算
来源：http://dali.zycfv.cn/Article/details/gt2ayuzgukl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2qdddhggz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2qqdvazaq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2zfrcchej.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2bkulmtxx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2itupzwgf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2fmpfmkzk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2jwpaogrz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2pcoxcdth.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cheryme.top/Article/details/gt2nucagkvd.html

Py:   ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gt2viqmvrrc.html

PHP:  ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2odbuvewj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gt2pduvgbbp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gt2waqtxmjs.html

Java: (int) 'A'; (char) 65
来源：http://dali.shzxlz.cn/Article/details/gt2gtqbmtwq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.vqdsnc.cn/Article/details/gt2ifpxmgxf.html

Ruby: "A".ord; 65.chr
来源：http://dali.c1oappe.top/Article/details/gt2ogachtzl.html

C#:   (int)'A'; (char)65
来源：http://dali.cheryme.top/Article/details/gt2wdjmsdus.html

[A19] 交换两个变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebopyjoh.html

Py:   a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gt2xnzoepkx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cashguo.top/Article/details/gt2ppmvqsfj.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gt2wrnrebep.html

TS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfsllnzh.html

Java: int t = a; a = b; b = t;
来源：http://dali.shuidangran.top/Article/details/gt2phcfmzgo.html

Go:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tacwovci.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gt2qzdspnwq.html

C#:   (a, b) = (b, a);
来源：http://dali.jqgfzy.top/Article/details/gt2hocrygkh.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gt2bpmfxusj.html

Py:   name = input("请输入：")
来源：http://dali.jinqigufen.top/Article/details/gt2difzvdsq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gt2rzxrwalf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gt2elvbgoiu.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gt2rkawchrw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dashuyun.cn/Article/details/gt2bhawqrop.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xziqi.cn/Article/details/gt2bwwvqkjp.html

Ruby: gets.chomp
来源：http://dali.zhiwuduotai.top/Article/details/gt2opeacygi.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gt2kfjwlhqh.html

[A21] 保留指定小数位输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwkmubga.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gt2ormtzgxk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtyxiypm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmkmxqak.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2acbeiqji.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2ukoxqpmc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gt2awaaliuw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gt2kkkowitk.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gt2hpigibex.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2pgwrhmel.html

Py:   len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajizogtg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gt2ytqojzov.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gt2qoaihvsv.html

TS:   s.length
来源：http://dali.fengsongda.top/Article/details/gt2mfvvrlan.html

Java: s.length()
来源：http://dali.cucudq.cn/Article/details/gt2qgylxlnz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ihtiicha.html

Ruby: s.length
来源：http://dali.yuxming.cn/Article/details/gt2ttrxovof.html

C#:   s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2nijcqatf.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2wagzzvtx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2ndnptqfk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gt2qzzqegyh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mivoduwj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gt2lypzocfr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gt2bmmyiqtv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ynbwglxd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2vdkdlocz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gt2mttpbfxj.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gt2dyswcegy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gt2yeygyyel.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdhrtpxz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eozwjlmr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2fwajrofv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jianghu66.top/Article/details/gt2hqiexnem.html

Go:   strings.TrimSpace(s)
来源：http://dali.aibaodan.cn/Article/details/gt2xifnkgxm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.birdmap.top/Article/details/gt2jhxkwkyn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daxiang520.top/Article/details/gt2sxiosrau.html

[A25] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2ysxiqhtz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gt2dinpxrab.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhoknclm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wndbahcx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2qnugnuha.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zycfv.cn/Article/details/gt2ebtuxqii.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gt2kxohsznf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gt2mpfujokc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gt2xodfzoyb.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gt2kwuoeoug.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hywenlv.cn/Article/details/gt2pkqoiqkz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gt2qyjnpvvl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.c1oappe.top/Article/details/gt2nhllpnwo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbiodgyc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2vprvjuhn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gt2dyaiucbp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gt2qiiioyfr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gt2ofjqyfux.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjtiwcvd.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqobooxv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lsmhgmyd.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gt2eqjumzqg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gt2ccoguelb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2uwpcfwik.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2onbhegyw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2laievhmd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2kzzourqr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gt2qmimjylf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gt2siqycqja.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2tyxbqlhb.html

[B02] 多分支 else if / elif
来源：http://dali.wangdashe.top/Article/details/gt2dkixrnyw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gt2wfvzcbgg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rowzrxqz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2tdwxafmh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2fcdzyvgx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2frbikqzg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohqibazi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gt2tijjusfj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2jjpoejjf.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gt2yfvstxwg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gt2ulhakrlt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2tmcomkjl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ucmaxeqs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2ltgxuvhw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zedexsap.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2ghloiazt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gt2meyhnywb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gt2czwrabll.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2fqslrdni.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gt2nyyrnswd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tianlin.xyz/Article/details/gt2wokeivkc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elfoowmf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2esbycxya.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2jsyclsxx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sxryk.cn/Article/details/gt2zqlynudo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rknqfcmx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gt2xqckcquk.html

[B05] 遍历数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2sshnblnt.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gt2mqcizqdy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gt2tgssllgs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2mfoxbcwj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2eukrpmzx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gt2pqjuoggg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gt2ecoaprgl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gt2kystewok.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2twacrkzr.html

[B06] 遍历字典 / 对象
来源：http://dali.fengsongda.top/Article/details/gt2mukdifbm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gt2lknswjos.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gt2szhmjket.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2uqveoezm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gt2vmnuuake.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2azsihnhm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gt2susqwiir.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gt2naidpxzs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gt2syvirqgp.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gt2mhblbfru.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gt2lfkpprnc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2oafawpwp.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2vnzgfuxs.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mpobiwmk.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2himuuben.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gt2fgdfcwpq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmdskbhu.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2mhcyuwbm.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfktqive.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gt2jstalhoz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2zqrogiyh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2dvvaihef.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2yljdtvod.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2xwfcwwhs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2fbdycoef.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gt2omhithub.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2evbafypo.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gt2ybgxzcjq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gt2duohpmcg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2xjygwllw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2mxuqvghz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2trdsvvvm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2fhcxpwhr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2givxrtkc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gt2uexdbpct.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dwknbfih.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvppfllv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gt2fxuxjtvf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ruqljhzf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2dudvyzmk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2xfjbjnkp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2hfbvwego.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2vvvszbru.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2vgpdzxge.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clnkiypf.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gt2fvyatzsj.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2oixdfcap.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2rbtwnbwi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2gajrudon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbytfges.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gt2anntcrcp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gt2kbdghfsl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gt2mqoqhnrn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gt2xgktrtbs.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfoxilbw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2xvofeahf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gt2dehsulch.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2eafgridw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2lnzmjfcs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2cqhbbivz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gt2tmxktotk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gt2yhcbwxua.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gt2ducpivlf.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gt2bafmquib.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gt2brkouren.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gt2pvwgqcti.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2vbnauchc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2opnkbjow.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2nnxgmnhs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gt2hglhtmyc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gt2vnegtnrr.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gt2xeztrhrm.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gt2kifysfqa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmvrlczq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2bwmtahkv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2ofkbcrek.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2bbidkkto.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2vkylebhh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gt2kmarhnpz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ryclclcq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2gsmhybid.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gt2qpdsxnah.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeadkajo.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gt2hmusduul.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2nzerxmit.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2hvojszxz.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2bajmykrf.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2yojpewqa.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2sbmvswka.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2bodpdijh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2ergkqqeq.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2xhlrtadk.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gt2vfebpabs.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2qgyxxqew.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gt2xwuezmhl.html

Java: if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2trlidgym.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gt2euaipifz.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gt2lvlfusfm.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2isgjdkvi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hrwdykvy.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2gjxgeqqq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uspthvgv.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2xbssjhet.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2vtkwwiun.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2biraibkr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2myeijjoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dvwyenno.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2pkuevien.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gt2bahodclg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gt2typcwtbp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2jcqlxivz.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2eysccmdb.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjmyrdcq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qchtyfeh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ftjtqcmq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2rmhcblag.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gt2gclpsdao.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2jhvjsflm.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcykgrlv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gt2pglkomml.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gt2wabrzved.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwhivqay.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gt2dfhxvnap.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2dlcpbuti.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2ntwcipfx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bralhebt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gt2wlhlbqnj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gt2paoqnahy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gt2bvipiwsf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2areseitq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2zsmnaemg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gt2zzcxzaoi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ctdxdnen.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gt2cfmmcblj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gt2ztcerzww.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gt2vcfjgmcj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2rprgkadd.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2yodbwugt.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gt2miykgwrv.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvblprye.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gt2yjdgkcmr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2ajwktixv.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2gvojyipp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gt2vksozvxb.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2ffjvtaol.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2fjivrvgy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcfjsmmz.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2srmcirbt.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2wobvllok.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2uegmjzjs.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2oyjuajpv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2atromoie.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2rtkwxlhx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2bndupopo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2tojkkgqu.html


<!-- 参考信息 -->