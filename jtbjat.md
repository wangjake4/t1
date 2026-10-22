代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtqzgkjaie.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtvljlpkvc.html

[A12] 字符串插值 / 格式化
来源：http://dali.hfpthk.cn/Article/details/gtdfaeghei.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fengsongda.top/Article/details/gtzxwgxbxm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.iojbl.cn/Article/details/gtvurjsynv.html

JS:   `Hello, ${name}!`
来源：http://dali.shuidangran.top/Article/details/gtamemnhre.html

TS:   `Hello, ${name}!`
来源：http://dali.redwolf501.top/Article/details/gtxqyampxl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gtuwijeifn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszmlqhkc.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsstcskg.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gtkifnkbfv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yangfankeji.com/Article/details/gtslwxxwiq.html

Py:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtjanhsfxf.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcebffscv.html

JS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtxclacjpe.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtluraarhu.html

Java: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtplytsyhi.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gthsmbpnqi.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtykdrjaqf.html

C#:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtixkzgjbh.html

[A14] 注释写法
来源：http://dali.havefunace.top/Article/details/gtgufrftms.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xziqi.cn/Article/details/gtnqsjgxwm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtoxtumjpw.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwybfnism.html

TS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtypffkcab.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigufen.top/Article/details/gtqdawpoud.html

Go:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtqnvgdsom.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shangyingyoupin.top/Article/details/gtzxnzibuh.html

C#:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtpodraoyo.html

[A15] 空值判断与默认值
来源：http://dali.316326.xyz/Article/details/gtefnksdaz.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtorqrthcj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtxzhwzbmc.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtlcipxuaq.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gteztzuzjh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fengsongda.top/Article/details/gtangmafbf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gtumecwzqe.html

Ruby: value = data || "默认值"
来源：http://dali.bjfxy.top/Article/details/gtwxtwjfar.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtoulcyxrk.html

[A16] 真假值判断规则
来源：http://dali.havefunace.top/Article/details/gtupbeaxzx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.mhx1999.top/Article/details/gtcjlmwkoh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gthjapgvgf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ybcxt.top/Article/details/gtxxiylmuy.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtnbyorlht.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aizwys.cn/Article/details/gtfxrwycop.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuxming.cn/Article/details/gtalcalerb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gtbispyuvq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtefmimtpa.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gtefcfckmj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtrsjhwutx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtnzqruthc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtlisdshji.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtdvpedgfs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtpldvytbr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtsbwrqfso.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gthjbtrdvp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtslghkkej.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gtrzdnjlkr.html

Py:   ord("A"); chr(65)
来源：http://dali.andypj.xyz/Article/details/gtofztkimx.html

PHP:  ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gttancpglr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gtnryhftoo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtgrbcvhob.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gtqsfwwnvm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlyztetl.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gtbftqdecf.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtyvxwljds.html

[A19] 交换两个变量
来源：http://dali.yanxiufei.cn/Article/details/gtgpcsbabk.html

Py:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtclqjvwrl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hfpthk.cn/Article/details/gtskoymwsd.html

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtpmbypzcd.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtesfikpfd.html

Java: int t = a; a = b; b = t;
来源：http://dali.cashguo.top/Article/details/gtzvowwpyv.html

Go:   a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtmzospsee.html

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtfbjcqnpu.html

C#:   (a, b) = (b, a);
来源：http://dali.jlsjyb.cn/Article/details/gtlkvpvwbg.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufizzgwt.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtftuthkqw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuetiantiany.cn/Article/details/gtirqwjsny.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj202588.top/Article/details/gtbopnsoch.html

TS:   // Node.js：readline 模块
来源：http://dali.jyoumei.cn/Article/details/gtarjdwtay.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gtmvlzrjxo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gtndsfvjve.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gtaygyrnqd.html

C#:   Console.ReadLine();
来源：http://dali.xinyue.icu/Article/details/gtsjmvzwtc.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gtckadbrsl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sysykeji.top/Article/details/gtlemqvcff.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtfldizbwg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtquhjlvvh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtoexqkuje.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtznsjlpyc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtbhotogln.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuffrcrid.html

C#:   3.14159.ToString("F2")
来源：http://dali.hammf.cn/Article/details/gtwwhibrej.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtvimnlbun.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtoybivjew.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.meibo888.top/Article/details/gtustbxcqv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gtjxxkdbcc.html

TS:   s.length
来源：http://dali.ppjwa.cn/Article/details/gtwvzsdmoo.html

Java: s.length()
来源：http://dali.yueranfly.top/Article/details/gtmvvskviz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinqigufen.top/Article/details/gtiswkctaw.html

Ruby: s.length
来源：http://dali.ppjwa.cn/Article/details/gtdpwgryuo.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gtwfpdyhqs.html

[A23] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtysspuliq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gttblcaxfb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gaohongyu789.top/Article/details/gtcoefgvfu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtraflthnr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtfeowojga.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gteeeqbchl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ydzc1.top/Article/details/gtqgsudkps.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtxdizpphr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.iojbl.cn/Article/details/gtqrleevui.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxfuchjh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gtxsfxovbo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gticexemjx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzznjwwi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gtrysrqyhn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gtidnkkiqi.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrcldrvie.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgwkmpsx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtutzypqbc.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtbjmmbytn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gtanukszxc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gthuwukabi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gtdshvlcll.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtkgutbczz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cqqwz.cn/Article/details/gtpzvnanes.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gttdjazbur.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sufxvd.cn/Article/details/gtdavtcgoy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gthtzezrui.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gthbglxiuv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtzjseqoqj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jianghu66.top/Article/details/gtdrnakqgy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gtvhmslbbx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtutiejjdu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqsmaevp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gttwposclk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtymhlqkii.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdohaiwub.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttbknaqmk.html

B. 流程控制
来源：http://dali.vqdsnc.cn/Article/details/gthngunwdu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtninkflfu.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdqkrsqo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtudkvfitw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzhauvwnn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtcstkyxuk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtqbuclzxp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtndkubsgr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jlsjyb.cn/Article/details/gtyxaioexc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gthefhswgj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtixcttgxh.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gtojgfcgpa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqhzdaea.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrjbuoyhy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrequwhp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtcbbkwbau.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtsrceihin.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gtngvhfxrh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gtsqfytbku.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtitvtcbdp.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtvndjbkvv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gtoxugwxmh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtljlznodf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtvszmdell.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtdgdybpyt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcdbjffrq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gtvyiytwby.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gtpbhlckds.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtzhkevegt.html

[B04] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtjasjlyxm.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gtbpnyioyx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytqumfzz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtjiyxceui.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtcjuktpsa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtymumvdsh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtcgsafcug.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gtvyjnfibo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gtuvohesve.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtcxumvaxh.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtsqbvzfvh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtivsuvipg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gttgiljkfc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtmvzuejcv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gtumipjhxt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtddgltzdy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gtcrbtebnb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdnqlezta.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtiwyfunpa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gtxfqipkrd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gtalykpbfh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtagsngpuw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtomgeoong.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtagsfwzzm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgseypfds.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtwfoagcua.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gtbrslaapm.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gtogqbxvjg.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtamxawusv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gtpumooyxj.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtvghecglj.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtrpqkjdvt.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtibszxpdy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtpfwtoqyp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yvedp.cn/Article/details/gtvmffklpw.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtpqcuttiu.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtuqwqxrbk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gtbwtcuaci.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gthniaoray.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtorluhyce.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtlxhlqctb.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtwrypaduj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gtioeptfzc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhiwuduotai.top/Article/details/gtyjbxkwxr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtcfamaesg.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtjcksslgj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlapxdtz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtxpspunwc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtrwanxjfv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtxoflgsoh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtplycovbe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gttujrrfhf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtdakcqucj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtndupuzgs.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtgxfjlqht.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hongshengwenyu.top/Article/details/gttxcfeuyu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtamjjxfrs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtjmgqdwix.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtayhrpxpr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtpknbepoa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtqrppjxqs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtqklclnrn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtwentebxx.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtxwuoefza.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gtijhajvrg.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtgkhcalbl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxabggzva.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtfjzildap.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtolevbgmt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtahpfsqya.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtfgpozrey.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtkutirlyw.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtmfkonzae.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtnrydsqzs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gtswninfqt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtlcqkkcre.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gttgnjuxzo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtnetdmxqw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtpsucsixq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gtcslxvrgg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtjjmgnhcj.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtkjgvdriw.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtmizaqpxm.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtbyrdvupx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtirjspdmr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtidheqjrd.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gtbxsunwkf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtoyewkawd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtsrvkthal.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtpkqpokoz.html

[B14] 判断值是否在集合内
来源：http://dali.zhoulong.xyz/Article/details/gtvyojousx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtklyhvxpn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtreorhzob.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtynubvycq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqvlpzsb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrnbnsygm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtaaqplarc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtwnbnjomf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtwrygxwch.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfwhuysu.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gtejygeimk.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtjukffekv.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtrtefcwcd.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtabkjcywo.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gttnamblrb.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtdtdsjuce.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtofvxuael.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbiajkeq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gtaraxuvyw.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gtagmgcasi.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtdfvhkgvi.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtmfhpusrr.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gttfocolnz.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtycmrrisc.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtfpgsrvwa.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtmwdjqyyw.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtdehzxbpo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpqittncz.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtawsayexu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtsmnocmmr.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmvifwsk.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtlibevxpq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtksuhpwwt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtdpsanocv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtwsymimfq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtponxrdxh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtvbvbfhhz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtvxivcgrp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtycotlqvz.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtuasruoal.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtrifbeter.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gteqfqtrlp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuotbofq.html


<!-- 参考信息 -->