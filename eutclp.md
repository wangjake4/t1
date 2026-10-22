代发 wailian999

[A14] 注释写法
来源：http://dali.fengsongda.top/Article/details/gt2qumrcixh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ppjwa.cn/Article/details/gt2mqrunqci.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2mcmdefyg.html

JS:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2ncevzcqv.html

TS:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gt2gzknrmic.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shuidangran.top/Article/details/gt2qlzygitx.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2zejidrjb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuanzx.com/Article/details/gt2ivzrdsnd.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmkmkmnz.html

[A15] 空值判断与默认值
来源：http://dali.tanke756.top/Article/details/gt2fywqjsat.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2bayhiwfr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gt2drrhdvkt.html

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gt2suswwhaz.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2qcuqxega.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jyoumei.cn/Article/details/gt2vnyfqhfh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gt2jnlvmspb.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpnfzcmf.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2gqxcmjfu.html

[A16] 真假值判断规则
来源：http://dali.yj20258888.top/Article/details/gt2pxserynx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gt2aomhnrob.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gaohongyu789.top/Article/details/gt2meryrggk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gt2oadnhrpi.html

TS:   if (!x) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2oytocaai.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258.top/Article/details/gt2pcxupjmy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gt2jorfqwvv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gt2qxtogekx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bdhyeebp.html

[A17] 位运算
来源：http://dali.nwbrower.top/Article/details/gt2cqwlrihh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2gsvvndnu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2umjdtpoj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2ibybrzhh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2qtgzfuac.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rghsobzf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2wevuvmjq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diejdgmj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ujkbdqdw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gt2nfkxipks.html

Py:   ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gt2geswhnqu.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gt2rjrgpteb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2stujawom.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lthagkzn.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gt2cvldohov.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yangfankeji.com/Article/details/gt2cczgcmkx.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gt2gxvmayvb.html

C#:   (int)'A'; (char)65
来源：http://dali.daria6918.cn/Article/details/gt2aqmsqdpk.html

[A19] 交换两个变量
来源：http://dali.fengsongda.top/Article/details/gt2febcaqex.html

Py:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gt2veioprfp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yueranfly.top/Article/details/gt2tnmkxwnb.html

JS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gt2bnvaimfm.html

TS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gt2fgpzrigl.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gt2jrcyeoiz.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwrbcazj.html

Ruby: a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2aitmtuuy.html

C#:   (a, b) = (b, a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihyzaufv.html

[A20] 读取标准输入
来源：http://dali.jqgfzy.top/Article/details/gt2lfpflneq.html

Py:   name = input("请输入：")
来源：http://dali.cdnleiting.top/Article/details/gt2mexocnrq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gt2mvbyyrmq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yvedp.cn/Article/details/gt2zuwkagcf.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2xdbscuff.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.iojbl.cn/Article/details/gt2ptdtvqkn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yonumen.top/Article/details/gt2oonujjbj.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmarxhc.html

C#:   Console.ReadLine();
来源：http://dali.jinqigfzy.top/Article/details/gt2mnfviidm.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2onwktbma.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ydzc1.top/Article/details/gt2gaaygtsy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2xaksubhv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2vaxzkzjj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2vmzclmhk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2lzvghapm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gt2jidwmdgz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2xzxvnybd.html

C#:   3.14159.ToString("F2")
来源：http://dali.sufxvd.cn/Article/details/gt2trlmihta.html

[A22] 获取字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2wpmytamm.html

Py:   len(s)
来源：http://dali.zycfv.cn/Article/details/gt2fikzgecc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ramhonnb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shktwrju.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gt2yvycxmjp.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gt2xfrupute.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gt2ytyyrfql.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gt2tjoyariu.html

C#:   s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocddgctj.html

[A23] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2aigquymm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gt2muabtjbi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpoueaey.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyufljsw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxyweysr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2fljgsvsn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyqmgypt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2pfgtolvl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fzhhl.top/Article/details/gt2ambeczet.html

[A24] 去除首尾空白
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dakyhslv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gt2wklydkhz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hywenlv.cn/Article/details/gt2wsheqthf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gt2zmykgjxy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gt2jrlrgkra.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.c1oappe.top/Article/details/gt2pschguoi.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gt2tasrlnqr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yongpay.top/Article/details/gt2scufmxbp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2nvuprixn.html

[A25] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2lwfroqvc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gt2waolkmed.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gt2qxorhuey.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gt2mpdbdney.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2hvebfljw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldvheymt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gt2dertcvfy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yueranfly.top/Article/details/gt2iczlwaac.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gt2xbvaapjy.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gt2msfkrpbf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ydzc1.top/Article/details/gt2izwkykcc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gt2bvevcljy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gt2vbppenka.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gt2cavtbcmc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2wsvjvwvq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yonumen.top/Article/details/gt2nmccbooo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gt2fwuocpkb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2wmpwhujv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2onughqvm.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gt2qbnszsij.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qzctexbc.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gt2qwiryfjr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.mhx1999.top/Article/details/gt2kswmqjpp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ivvv.top/Article/details/gt2kyycrbih.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2iojyumik.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gt2xtrvlpsg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2mmsszpmm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gt2rvyetxol.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gt2uxnqfmzw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2kmnpjfse.html

[B02] 多分支 else if / elif
来源：http://dali.9152youxi.cn/Article/details/gt2roghoqrc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gt2fbyzwhfj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hfpthk.cn/Article/details/gt2nfxmghgw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2oasqrqrk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2ckdcbjfn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2blfjldgb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gt2wglfrliv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.svipenyu.cn/Article/details/gt2wuthstup.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gt2katmmmog.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsvituvs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xinyue.icu/Article/details/gt2wfrwlmqy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2cryrhzkt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2syjckrga.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2ififcudt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2pbvnyign.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2qhypgojw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2fhrjkmpm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gt2grvaocug.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2wikgfhhq.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gt2zpwuhajp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gt2ntsrkvet.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gt2npomqvgu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2gzohosbz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2kzjhbbon.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gt2bcwtynqd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tanke756.top/Article/details/gt2avdylnoo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skqhvuaa.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2cnrvcceg.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gt2mddzpvcq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hfpthk.cn/Article/details/gt2txjdggif.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2icricsiz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gt2mcbdobyy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gt2wxezxnld.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gt2rgwtenmg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gt2odosdxee.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rqlkijcc.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gt2acjjlzwx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gt2yshskpys.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gt2zgrimbus.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gt2ikmnhtqr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hsvncrwp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gt2ujuvvgly.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gt2yjulqieu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gt2flgvcogi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gt2yxcqsajt.html

[B07] while 循环
来源：http://dali.fengsongda.top/Article/details/gt2qjfocpln.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gt2avajdqia.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbagzefr.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gt2tmmkbwdh.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2bkxzotdx.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2dlqtyccl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gt2itjlcqwu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gt2laswcity.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2kecquzxq.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gt2ohouqxac.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gt2xvxjpejw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2unwcwpbh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2ebnzipbe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2iswehxyk.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkjjtwzz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gt2mynlljvg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gt2gkcgcofm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2sfzygfpe.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gt2nckwzrda.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gt2ubulttfa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2gpsxevmg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2xzofdlfr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hchkrncf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2hlxgwuuj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2xqxaercy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gt2kzeutzpq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2iizbdmrn.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gt2gvzirrcg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gt2tlxopwgc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gt2reilhzsw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2uaajumoy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2hvrimmdv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gt2qawyxdig.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xylfe.cn/Article/details/gt2kkkrvtwo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2udjwlsbm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2svhqofaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gt2lakimcfe.html

Py:   list(range(0, 10, 2))
来源：http://dali.dianchejie.cn/Article/details/gt2beufcvjm.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2ikugfgxj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2rufoanaz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxewhfqd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gt2zdmycrza.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gt2ykrqvkxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gt2pcqatmpm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2skasvqml.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gt2onbwogem.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gt2iplxpbqf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlhitlsg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2woknhmby.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2hkjsiwuc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2laazunce.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gt2yihklwzx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyrvcptz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gt2ursmzaap.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2lesxkihd.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gt2ctqkiwcm.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zonjgfxp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijwgiqkm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2ebkqrccj.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gt2zgufnaiz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gt2zznzqmll.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gt2hjatafds.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gt2gtxjhgnn.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2liahxvvs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gt2kuyjzttd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2okruzrfc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2xcrulmms.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ubsgnrgk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rfetsqsy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gt2kkbngmqu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhucpnia.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zilmybuc.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gt2tdvififb.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxtvpapj.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeqpkwkf.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2jmakopos.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2nxoiqicb.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2qjjcqwbd.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2ghvpbqna.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2rkqjbimb.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2ggedanqa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2xkscihgl.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gt2ibhmsxdq.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gt2rvfbxjhm.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2luycqhqk.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gt2zbthucwv.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epqedfdo.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gt2mjdzlrhf.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agcsxarw.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2mtgmlzuo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rzicqblg.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gt2yiwcmssg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vfmnlzze.html

[C01] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2fxrwszvh.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2ygaxiabz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2icqrtsje.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2mbcbpoty.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2dpvtashi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2llrpnhmh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uskdwksb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2motholeh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2jyktguea.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gt2dqslhgmu.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gt2cdhhjffz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bumuavrl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvhbwnvl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lldvtror.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gt2hjlrwirk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2gironeqr.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gt2ighehqvv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gt2vgvfopfp.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2toyivrbt.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gt2wbttgrwi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2eazgetfw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgocmaco.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dxnknopj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gt2auhxogxf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gt2scbvjcch.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2irwkkawi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gt2wlqlagyh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2cklsmplm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvozwada.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gt2hknyfwnn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcozcsxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2smqllmyx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gt2vluanmzo.html


<!-- 参考信息 -->