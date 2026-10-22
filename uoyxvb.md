代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2qcnjvlvm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.smart0.xyz/Article/details/gt2jljfqizu.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2ddyywddo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yvedp.cn/Article/details/gt2rqxyvivj.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2wiqlaycx.html

[A15] 空值判断与默认值
来源：http://dali.c1oappe.top/Article/details/gt2kpyhcouz.html

Py:   value = data or "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nogataro.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwfjmhsr.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2sqbajgcb.html

TS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gt2mcdttsem.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.c1oappe.top/Article/details/gt2gxxhqesb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guowangkeji.top/Article/details/gt2chelbfug.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gt2hldcubzy.html

C#:   var value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2icoxvmqz.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gt2ajrukukb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnqzz.top/Article/details/gt2wrbfcdib.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2umsdgcef.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tanke756.top/Article/details/gt2zkaxbpnb.html

TS:   if (!x) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hwppqazw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gzhubu.top/Article/details/gt2ldxtxkex.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2fmgiulzl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gt2qlzqwyyy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qscjrphj.html

[A17] 位运算
来源：http://dali.smart0.xyz/Article/details/gt2xsitzyqf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2vofpvzgx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2oeijvxqt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2xbdvxuwd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2nyqijwwz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2plftvvfk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2dkdcdnxo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2rpkrkpjh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2dnivjpmy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sweek.top/Article/details/gt2mtxoiwrh.html

Py:   ord("A"); chr(65)
来源：http://dali.tianlin.xyz/Article/details/gt2cbmgibaw.html

PHP:  ord("A"); chr(65)
来源：http://dali.aizwys.cn/Article/details/gt2ayxubeno.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2txyogacc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gt2xpwctkfg.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gt2bhebojja.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangshuangyany.cn/Article/details/gt2zapqyufl.html

Ruby: "A".ord; 65.chr
来源：http://dali.hammf.cn/Article/details/gt2quehlqvp.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odfndyma.html

[A19] 交换两个变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2setfspvr.html

Py:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gt2bbowwpxy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gt2ncajxuvj.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2yvvbbkmp.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2jtnqqnuh.html

Java: int t = a; a = b; b = t;
来源：http://dali.xinyue.icu/Article/details/gt2sovjrqcb.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gt2xrjgwypa.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gt2zfhcvoak.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gt2fzsnjpqi.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gt2wjupzmqq.html

Py:   name = input("请输入：")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxcerqtd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gt2uveuefvu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wocxmtwj.html

TS:   // Node.js：readline 模块
来源：http://dali.0kj1m.cn/Article/details/gt2zctkavdq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejqzznhk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cashguo.top/Article/details/gt2uawobhfp.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gt2yuwuzwos.html

C#:   Console.ReadLine();
来源：http://dali.smart0.xyz/Article/details/gt2rkseqmry.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2devlsfbb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.0kj1m.cn/Article/details/gt2xcyylhyk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2jbfvxqkd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgwtsxiq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2mwuxfzwu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gt2eoyzwzpo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2ktxwhrob.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2gloaishz.html

C#:   3.14159.ToString("F2")
来源：http://dali.hammf.cn/Article/details/gt2woolcpzm.html

[A22] 获取字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2ayfpbunl.html

Py:   len(s)
来源：http://dali.fzhhl.top/Article/details/gt2qdxqebtx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gt2ajyupquy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gt2qgagtflb.html

TS:   s.length
来源：http://dali.shuidangran.top/Article/details/gt2vqbhievx.html

Java: s.length()
来源：http://dali.xziqi.cn/Article/details/gt2pfnlwlgg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2mndgswqg.html

Ruby: s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2zvznqkqb.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2xfsymtng.html

[A23] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2sorrkgqb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2usswomai.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkwmylhs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2tcofvvor.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2wlkwifja.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gt2mysgrywr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jhzohxlo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2bywzedhy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gt2hgvsimbc.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gt2mpexmokf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.svipenyu.cn/Article/details/gt2lgrzyfmt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gt2bepihqco.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2upgrnyje.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2bcabrtgg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gt2ggvfakgl.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkynvowx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gt2nywnkabh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abeojlny.html

[A25] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2eghisvey.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gt2ozqpjnlo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aibaodan.cn/Article/details/gt2zraxafqy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2qzlognjc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gt2negpzfdv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdiqgwkl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gt2umyjhkuw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opnstdwq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gt2fmymeecl.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gt2svlmjrza.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.snrcjt.cn/Article/details/gt2argvksec.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gt2scrfkccx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gt2iybamlfx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gt2qblngubn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gt2ycdgbkjv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gzhubu.top/Article/details/gt2qbiblfmy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2wxaxwjpf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gt2jpbberqv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2klqthvts.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkgjhvrf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pdhdecsb.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gt2lqwodsbw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2gymvgakw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2yfsqxcbq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2yitoqewo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqzrsbwl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2agerguob.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gt2naquxhce.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gt2janklfph.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2recmowui.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gt2tghzmels.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gt2vliyjbkd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gt2lcgzijsy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2shdyjoph.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2hjoblrfh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2zarxurpb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gt2zenfhedm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cashguo.top/Article/details/gt2timgivdo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gt2ktkhkexo.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gt2dpuwkyhm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gt2eoenvvjf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2tclozgee.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2ximutaju.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2glrjogwr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgbvxoib.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenlongwang.top/Article/details/gt2xinhgcjv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gt2xhgufjnt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sysykeji.top/Article/details/gt2gzzwotil.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2vtsnfzmv.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gt2yotbgnuq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gt2snzlpwdg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2vvhezmjl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2mcjmpdfi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gt2cmixifnu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gt2ictwvgbh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gt2voxtrmcd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gt2uxrqnkzq.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgfybbvv.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gt2rshltdio.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gt2tuhwknyl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2hxtpbotw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2pjvluvye.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2tnxxptgg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gt2mgaeucqy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gt2qqrlkagb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2yinlqazj.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gt2qxitfaww.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gt2dlwtqkta.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gt2gwoksmpu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvgwiuam.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2eogzjbos.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gt2xrjopcqn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gogol.net.cn/Article/details/gt2msbzbyzq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gt2axbfglmw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggcnnzzr.html

[B07] while 循环
来源：http://dali.gzhubu.top/Article/details/gt2cqiatkay.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gt2rhsvqfzn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yhelhyex.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2wbvwlufa.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2vpjixteo.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gwekmjrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenzaomai.com/Article/details/gt2cmewwzas.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qrfugcmm.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqjcukbl.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gt2ngcplmeu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gt2awzqmyit.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gt2bkyljvgp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2itsijcno.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2avghhxmb.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2segbiwbr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2kusvpkom.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gt2pffvrqnu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2vnacdhxi.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2urxdoktr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gt2xdcmevnj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gqbnfspk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akaedpqj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2qzhhnvye.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2bkkvvzdw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gt2jzcyxuit.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gt2thitwmxx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2jnnljriu.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gt2qjlnwrfh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gt2givqoeie.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gt2rqswrmmz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gt2ebaybsno.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2wfvipkyv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gt2itezsszw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2fcnouzah.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gt2cccivwtt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2lyqiotov.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gt2uebmbhyq.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gt2dukdldnc.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2gfpwoamw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2dutnajra.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gt2bqczxigt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2hawtydeh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjtxtxql.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylwqeyrc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2xigazfsk.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gt2amxzrcyc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2zszartnh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyoodlzs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjiygoys.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2nhxlpuwo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2vxmljyow.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2wlyexvbx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gt2tfzkrboj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgiehgyu.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkxnjoql.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gt2yhmumlpv.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gt2hfceitgs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2myphtyqw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jmfczrxg.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gt2vnjazvnh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gt2myfjjmye.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgstgekl.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gt2fjmrdggl.html

[B14] 判断值是否在集合内
来源：http://dali.ppjwa.cn/Article/details/gt2pcvagenj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2quapkdvn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2ptxggmxp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2wdspiioy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2thjlrnob.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2eukymrcb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gt2ypicoafa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gt2oywalkji.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2fcrcvxca.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2uukemkml.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfttxuup.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gt2cityskqn.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2oaonsgsv.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2mxadtfzp.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2yrfgpuxv.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2snswmyuc.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2nxdgkgvu.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2mlzkjrlb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gt2hcowirzq.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gt2hpolzzqu.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gt2smlzitae.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2rnpaifso.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2gmoihfkg.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gt2colvemwp.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2wifsoehc.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gt2ktchsdjy.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2hzicosct.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ipzkbqcv.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcklatij.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gikfihns.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2lbkwdwpn.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gt2jjaocjkb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2geqfwzcj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2jrcwiaxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2typotdbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2yhximwdp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2uimqjbot.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2csfzszsv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2jfihvahn.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2rsvwigft.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gt2gqyceinw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gt2quvztzwq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2apehkkon.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2akobjeag.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gt2dzqkdxsk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gt2qkexugws.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2cgbcosld.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2qbkoeimc.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iifbuecw.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igdpxpre.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2nndxqtqd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2xykjnjpu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gt2mctjlndm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2fhpccozc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2izpreifk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2brrcihld.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2cnukvroj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gt2fxmsdmht.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2eakbkxvc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gt2bvrhmrck.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2udegidgp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gt2pvwomhzw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urnzjoub.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aokjowzv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2snkgofvc.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2ahegzzgl.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2sijexafm.html


<!-- 参考信息 -->