代发 wailian999

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtpmdzgemf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtbldkalhg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtwgusifzw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yueranfly.top/Article/details/gtkekgqfpe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtwfczpsdu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemxnqkic.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtbdzwoipr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuanzhike.top/Article/details/gtpjfruzbr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gthhjbjxlg.html

JS:   `Hello, ${name}!`
来源：http://dali.jinqigufen.top/Article/details/gtocfhyvlf.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtbkrkmbgr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gzhubu.top/Article/details/gtvzehdxqa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guannengcc.top/Article/details/gtxmltxwft.html

Ruby: "Hello, #{name}!"
来源：http://dali.guowangkeji.top/Article/details/gtqgkqfttb.html

C#:   $"Hello, {name}!"
来源：http://dali.c1oappe.top/Article/details/gtouipaqxj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ivvv.top/Article/details/gtdhkkzawr.html

Py:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnkkidic.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtnwikqwbe.html

JS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtdkhdnntr.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxzhnjly.html

Java: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtbrdtvkys.html

Go:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtgsgvohit.html

Ruby: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtqwlmftpb.html

C#:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gttaaudqzz.html

[A14] 注释写法
来源：http://dali.guowangkeji.top/Article/details/gtltsngwne.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.fzhhl.top/Article/details/gtqjzsywps.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnlppfoi.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtgxvxpgje.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtdtlgaxfv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaweohwa.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtdakzrlcg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.pycfn.com/Article/details/gtqitirrvt.html

C#:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtmstuesvc.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gthnnpvlqf.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gterrwrmsv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gthjvlxheg.html

JS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtmypaoyot.html

TS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtlelgwyth.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhixingplan.top/Article/details/gtyczkfadp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.316326.xyz/Article/details/gtigbwpiwj.html

Ruby: value = data || "默认值"
来源：http://dali.pycfn.com/Article/details/gttheswjav.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinrnoqyu.html

[A16] 真假值判断规则
来源：http://dali.yj202588.top/Article/details/gtwlntxwbr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gttyntiruh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgfzy.top/Article/details/gtvhnfpuuo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuxming.cn/Article/details/gtrelpetje.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gtqoljokvv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aibaodan.cn/Article/details/gtcyeyyigd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gtnjfvurlt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkquxbymf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzkanpzad.html

[A17] 位运算
来源：http://dali.9152youxi.cn/Article/details/gtdubhptyp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gthpcazxby.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtxwkgahvs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtmkjyhkjk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfccugdsb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtxbpgwxcv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gthnhgquhn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtigklsnyv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtniortart.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangshuangyany.cn/Article/details/gtjphtetrl.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrozwjgyt.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtefluwytj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtfjzgbqqa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtmaydznzb.html

Java: (int) 'A'; (char) 65
来源：http://dali.svipenyu.cn/Article/details/gtujfsvzzd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj202588.top/Article/details/gthbczgqdc.html

Ruby: "A".ord; 65.chr
来源：http://dali.mhx1999.top/Article/details/gttqpszako.html

C#:   (int)'A'; (char)65
来源：http://dali.yvedp.cn/Article/details/gtkreoqxsc.html

[A19] 交换两个变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhydqaia.html

Py:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtrsenmudb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gthgwzhvza.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gtrqxkxejh.html

TS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutuuyoyg.html

Java: int t = a; a = b; b = t;
来源：http://dali.cucudq.cn/Article/details/gtfwilwatx.html

Go:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtluzaofrp.html

Ruby: a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtprazyyhu.html

C#:   (a, b) = (b, a);
来源：http://dali.jlsjyb.cn/Article/details/gtgcpgodim.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gtatadqkcq.html

Py:   name = input("请输入：")
来源：http://dali.mhx1999.top/Article/details/gtvzzhoqtd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtrxmdfisx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aizwys.cn/Article/details/gtbqetdtcp.html

TS:   // Node.js：readline 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtwibbxbka.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtjbrlfnhb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cashguo.top/Article/details/gtbhekpxfq.html

Ruby: gets.chomp
来源：http://dali.jinqigufen.top/Article/details/gtvwpnsxer.html

C#:   Console.ReadLine();
来源：http://dali.zhengqikj.top/Article/details/gtbdcqrpsf.html

[A21] 保留指定小数位输出
来源：http://dali.haohaochexian.top/Article/details/gtoebumpqf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuanzx.com/Article/details/gtaevlwihp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtmhphzbgn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtslzqudpt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtmkkrsvyw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtdnwkbafy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gttxffhwhn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtgvrzxctk.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtgwagfssg.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtkeeyioez.html

Py:   len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxhuemkni.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtntlutkzw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yonumen.top/Article/details/gtviqfgeem.html

TS:   s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtgqvdchnn.html

Java: s.length()
来源：http://dali.meibo888.top/Article/details/gtifoojalw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gttfnmjkgl.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gtckgkdpqw.html

C#:   s.Length
来源：http://dali.chenlongwang.top/Article/details/gturyixjfd.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtgjubfzby.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daxiang520.top/Article/details/gtmwodaslq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtmwynlogq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtdhrnhfik.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtoykqhejx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtostcbgpg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.haohaochexian.top/Article/details/gtsitjltri.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtverbezpa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gttciwkepe.html

[A24] 去除首尾空白
来源：http://dali.0kj1m.cn/Article/details/gtagvqpdgk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.wangshuangyany.cn/Article/details/gthacqqnps.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvptmuxqw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtlcxbnzrl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtmefbcszz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gtfapiyfge.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnqzz.top/Article/details/gtlqcocbex.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aizwys.cn/Article/details/gtgayyrbhy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jianghu66.top/Article/details/gtwboelaqr.html

[A25] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtpgdzvqve.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gtpmprdghr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gtrmzsfixf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtdvqncwku.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtscalwjva.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gthrbepzhq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtskiesltt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gtpazemuli.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gtsblwcyac.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gtlmueahpu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxuanxn.top/Article/details/gtffdjutyx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gthntcyybp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtavfcfdun.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtkmhkqnku.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gthjalkfxv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cashguo.top/Article/details/gtpvqgaqxq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfyputrp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtsyuudzei.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvcuphrqy.html

B. 流程控制
来源：http://dali.nanxuanxn.top/Article/details/gtizlnmzdh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyxucgbeh.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gtujlwkfxg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtkvphhafm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtkglggwgr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtsynwmzru.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtgeyempxe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtfjntdiog.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gtfnkanpmc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gtcnnxccjc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtchbnjzkq.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtmefokgko.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtxdtsmhxc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gtcquaokce.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtnfucmebc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtmxsbfebj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gteiasdvgn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtrbdgkjtp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtuarwxpng.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtepycekxw.html

[B03] switch / match / case
来源：http://dali.yongpay.top/Article/details/gttquqvocu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtmxkoicez.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtaqcgwznj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gteqjzwxhh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtyzojyisd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtqyryutiq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gtcewefhsy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gtrijvjizf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtjesxarsk.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtbwoaugzy.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gttfcwyoun.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnggipyhe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtsprcasgk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gtbpbmmcbv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtichrqmtd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gtsqshnlvt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtposqrobn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtkrsyrpgq.html

[B05] 遍历数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtcxcxzpvj.html

Py:   for item in arr: print(item)
来源：http://dali.wangdashe.top/Article/details/gtzdqlsbmk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gtdedqakqy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtawqixqkc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtswadxtyz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gtvcbgrtit.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtmuchdbkj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtwnxwzhxt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gtaysryxpy.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gtiilvkbjy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gtjxtppvgq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.0kj1m.cn/Article/details/gtdaxvgine.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtyialfdwl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtuwayaxnh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtrpdyctdt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dianchejie.cn/Article/details/gtdlspmdnf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gttcoqnklz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtvnydrerm.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtnyuvwzrd.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gttprlxmjz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gtqhjwiatl.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtfisiovqq.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gthyfnfjau.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtbzdtqjlf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gtnofkcywz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtnukzdgol.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtgznmsimy.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtncbpyauc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtsnrqxusd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gtgsgbcjql.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtppupgesz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtphhwnoas.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtytbzgyuc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtnmkoxrdg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtofrvpemk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtrsizdaww.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gthyywcncv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gtvrsnfrql.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtllubjwgl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtngmozouj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstjptoaf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtgxavsvqm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gtidcpxgtj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtfjgkosvh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtukbksryw.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gtboqnhuqr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtkiilwppz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gtdjgsrfqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtmhrfzkdb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtrjfonwub.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtvwxujpss.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtrobdocwy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxuanxn.top/Article/details/gtqucgdfxa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtzamodegz.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtscyfpmsa.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtqimujmuh.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gtoslshmmd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gttrjgpjpq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtowjuliwv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtbcyljyjk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gthkkvcakd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gttfnbivnj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtfbsxwjtz.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtrwoxdfwh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gtevqutgia.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gtaznlfppj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtyfwnnpbo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtjuaxfdih.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtksykwwof.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtenntquyy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gtmwktiiwj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtwoiafokg.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gthazcvzoc.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtkaaalpfq.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrocsoovn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtilvouavo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtuxobfilj.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gtgvwrpzsl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtckbjuvns.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfuunxgc.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtiiqnnifb.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtlubipzzl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gtofxwnqfu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtfmgqjoef.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtslcrvrro.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtluebhvnt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttgpnkuvv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtswsincqn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtnjeefueg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtizerxuej.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtmhaxoacj.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtaleiqyxi.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gtyssapeir.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtlfyyowhh.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtmjgygrkw.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtvngeprvq.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtiopmwckg.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtzumglsmk.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtviiaamlk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtrfuvlxon.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtjudxsbxq.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtefefasgx.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtjkwhzqwq.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtepxykyuo.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtypcdrqib.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtaaujprsy.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtuuxuemwf.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtlbrlzsyy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfzvypedk.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtclxeuzmy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgfyfosnn.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtbidolumj.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysaqkgjy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtwxyhictj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtcrkzkxem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtgkofdkdt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gturtjhjyl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtgyqiwhgy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmqrlutlo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfuacdoue.html


<!-- 参考信息 -->