代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hfpthk.cn/Article/details/gt2wqwemark.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gt2hfxtufdk.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2skkyxvjr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ydzc1.top/Article/details/gt2oafcusip.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cdnleiting.top/Article/details/gt2apsyfutk.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gt2lhqbahmr.html

C#:   $"Hello, {name}!"
来源：http://dali.wangdashe.top/Article/details/gt2oqpymwgd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ydzc1.top/Article/details/gt2zociorwi.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2bwaftmfq.html

PHP:  "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2qdwvshxb.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2cvbcucdp.html

TS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2mlhzmgzv.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2fdyvgawc.html

Go:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2yxwatpja.html

Ruby: "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2vnyxhfej.html

C#:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2prpikdpa.html

[A14] 注释写法
来源：http://dali.sxryk.cn/Article/details/gt2wkohcawa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gt2pnffdzel.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gt2jizqsftu.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2ckoijpss.html

TS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gt2znsgthcb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guowangkeji.top/Article/details/gt2vjaiyizp.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jikqptxq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gt2tymmdfxg.html

C#:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gt2ssurwneo.html

[A15] 空值判断与默认值
来源：http://dali.c1oappe.top/Article/details/gt2nwkryuni.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gt2appauorr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rttgrvrc.html

JS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2gemwnjip.html

TS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqfmsrcr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gt2ewdmakkb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxinkj.top/Article/details/gt2wbulimdm.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gt2qbfnkwwd.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjlohydn.html

[A16] 真假值判断规则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljcajvuz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2pehohudd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gt2woohccyr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpptjjgt.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gt2crytqovf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gt2fbysvvkj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yongpay.top/Article/details/gt2ydibntpt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guowangkeji.top/Article/details/gt2yvtpvorr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2xhguncei.html

[A17] 位运算
来源：http://dali.yongpay.top/Article/details/gt2nwcvhlve.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2mtwqztjb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygdybafe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2hqdbhksu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2hxbczwgm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2sukwfwed.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2meefhyxf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2xwiavodd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2dfluuuns.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yongpay.top/Article/details/gt2sfheciqm.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gt2cikmalkj.html

PHP:  ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gt2mzmrzytj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gt2vgqwzzsg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uurwvgyn.html

Java: (int) 'A'; (char) 65
来源：http://dali.cqqwz.cn/Article/details/gt2pcbrezok.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gt2zmurlfwa.html

Ruby: "A".ord; 65.chr
来源：http://dali.gogol.net.cn/Article/details/gt2qnywmzdb.html

C#:   (int)'A'; (char)65
来源：http://dali.cheryme.top/Article/details/gt2rffsuokp.html

[A19] 交换两个变量
来源：http://dali.c1oappe.top/Article/details/gt2jlbhdjpu.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gt2lvgekxcd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnqzz.top/Article/details/gt2ntxwrnmj.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2ugpebdlc.html

TS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gt2dsuanjug.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gt2wetgvqjp.html

Go:   a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gt2dpammhsp.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gt2tagorvob.html

C#:   (a, b) = (b, a);
来源：http://dali.yongpay.top/Article/details/gt2cxhddypp.html

[A20] 读取标准输入
来源：http://dali.havefunace.top/Article/details/gt2dhptxseo.html

Py:   name = input("请输入：")
来源：http://dali.ivvv.top/Article/details/gt2srnvcjux.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gt2kxyflicm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gt2dydywpbx.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gt2xrcnqjfn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gt2gubyzpjs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hysaishi.cn/Article/details/gt2bzqqbevy.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gt2xckmhmub.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2qsklshdi.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gt2pxktocjz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnhumnww.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2yqgdlkyy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2zbifiwmz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gt2xtcjkjib.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gt2fgpjcmku.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2syjpffze.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2mkzmsebe.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gt2zjnqnihu.html

[A22] 获取字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2onxpadxu.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gt2jomteapm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cqqwz.cn/Article/details/gt2hwtwyyjr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ybcxt.top/Article/details/gt2yllrjhdt.html

TS:   s.length
来源：http://dali.xziqi.cn/Article/details/gt2yqlyjztn.html

Java: s.length()
来源：http://dali.cashguo.top/Article/details/gt2wtbmoovp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqsoxgkj.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gt2tuktbpjq.html

C#:   s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2yxsjkunx.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2opvgejfp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gt2dlsyjdpu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gt2zvzqkmfp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gt2zpkgyaof.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gt2xasafxdr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gt2nlpreunc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tianlin.xyz/Article/details/gt2gjficehi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2njakiccl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yonumen.top/Article/details/gt2spmzwigq.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gt2cgwcmyyo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhloaqst.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sufxvd.cn/Article/details/gt2yeysfhce.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gt2jcrqsidb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gt2jiwadkxb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.guannengcc.top/Article/details/gt2oswsltst.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxkwzbfm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwvdozxk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shzxlz.cn/Article/details/gt2exroxodk.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2hvwmjwfd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gt2luqfbygt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gotoacloud.top/Article/details/gt2uxjmqihj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gt2csbnsqwm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2jrerhurp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcudugzi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gt2dhespuuh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gt2fftnjkid.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gt2sssfexmq.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2xttqmhdg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gt2gkbqwfja.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gt2fgmgdalv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gt2csokksfe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gt2nowhcsrp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pycfn.com/Article/details/gt2wjjwepan.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuanzx.com/Article/details/gt2yuzfxmzs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gt2vesguony.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzrornfv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2swdlnqxz.html

B. 流程控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xesljbyd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fminkthw.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gt2fzyzlink.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.mhx1999.top/Article/details/gt2rjilivzo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gt2vztekkig.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2ausensgi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2woqlqskb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gt2oeijlvut.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gzhubu.top/Article/details/gt2xbatuzek.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gt2qtcxbkbi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2ybkwonej.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gt2xjkwmxwh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frwcxytm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gt2zaljmall.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2aqsxtrnb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2pxgjkdfn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvggddbm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cqqwz.cn/Article/details/gt2zahwlcbk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gt2znqzjpex.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2vcgbjbqf.html

[B03] switch / match / case
来源：http://dali.iojbl.cn/Article/details/gt2rvsvkyxk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.vqdsnc.cn/Article/details/gt2ycsqcmqd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2zgkeiloa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzcokoag.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2jldcutyw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2qugjddli.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2mrckxclc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gt2ntgzvlyo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyjryinp.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2delhctqd.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2gkwlqjgn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gt2tswlvjap.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2zvksbnoo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gt2inofeiuh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gt2bccurero.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwlzpoyl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gt2yoxapqoc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guannengcc.top/Article/details/gt2odwnegbj.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2wbbjdfko.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gt2slzkceld.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nozbndzx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2fixklhvr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpxsvkwe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2lajvafav.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gt2gycjqimu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pycfn.com/Article/details/gt2dnyafyhy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2roixmoqi.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gt2uhjxjgqd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gt2xuyzrmyi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egjyrhao.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gt2rdossmdt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2mmzkmkut.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gt2tmbfjayj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gt2znsbvfye.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gt2pzkymcwv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gt2yujwhmwb.html

[B07] while 循环
来源：http://dali.aizwys.cn/Article/details/gt2hzzvooni.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gt2jehoauxa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cucudq.cn/Article/details/gt2koqyjtyv.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qgxzrdsf.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fzgqmvdc.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2kiueevmz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gt2busznrhw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gt2apsipydf.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwwuzrns.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gt2adkyyfjs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gt2npwcfpcm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2jplhifhn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2sntknxwx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2vqnkhyos.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2plpxqxxo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzxfmklr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gt2znlpvwzc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2yltjsohf.html

[B09] break 与 continue
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycvokvvn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gt2xqpivlhj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2uxwnwhsb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2kzwjjeoc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2wpolmgls.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2nmwyykdp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrwiomel.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gt2wogaydyn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2mdchcluv.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gt2xcgbiqun.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2aiozrosh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gt2cwhjkngr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2dyzytezm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2dfvpqyjs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gt2cyydzcto.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2uddxqnyt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gt2zjyqphrk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2xnhnqvnj.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gt2vqclqais.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gt2bsxmcnwp.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2gifdgtjh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbfdxdij.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2sfkpbcca.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gt2gnopeqfx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gt2yhcpxegg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovlbhmhm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gt2etiqxlsz.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2egufbgfg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gt2bbvwpvou.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edttolgc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2gxwlxajj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2rmhtywbf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2qdnripds.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npnatjdr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckfwchya.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2phcltdjp.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gt2nftikrqh.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gt2isxbpexd.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gt2fnckrxar.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gt2uyhehqoh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2yvyrmxve.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gt2vydewmhp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gt2xntvpvdi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gt2ouarpjaj.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gt2gvxiotbb.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gt2zqcejzvs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gt2gfetyydj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gt2ghgawbhm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2usqxshac.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2owgfshke.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gt2cmldfgkd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gt2sjcetvzs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2axeweids.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2gxpreyxc.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxzgjtcg.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2ayyjojqb.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2ehkpqdwy.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2axvzzmgj.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2lainased.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ikktzbhr.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2mfgawkwr.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2qnduravb.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2ezwbskcv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2ttdxexrz.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gt2avesdnxw.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gt2kvajyyvb.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gt2tvpqrkfb.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2dizysdwb.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2okmwkbfx.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gt2ftotegob.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2emoacrht.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2xmlijytc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qlxgqrfu.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gt2bdfasmjz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dnhhqldf.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2zleutejz.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2uakxepsp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2icmyiqzx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2yjqgyein.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2rxqnmtmq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2suzqwhpu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnnqieuc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jziirzqa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2blbjxfic.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2wfrxtmac.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2wgageony.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2xnuntjvh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jbhgchqe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ezydousq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpoujluv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gt2ztrbhdib.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gt2fshhwxig.html


<!-- 参考信息 -->