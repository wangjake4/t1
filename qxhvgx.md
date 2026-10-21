代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xylfe.cn/Article/details/gtztwoxgnp.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenzaomai.com/Article/details/gtwcswlojy.html

C#:   $"Hello, {name}!"
来源：http://dali.0kj1m.cn/Article/details/gtfarmwjwd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yanxiufei.cn/Article/details/gtcuughytn.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtnajkqvij.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtiakesofb.html

JS:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtfxyiscdt.html

TS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtnbbyxenl.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtyrbfhyvs.html

Go:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtnjqssepa.html

Ruby: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtzoiagpqz.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtbfsnznyo.html

[A14] 注释写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqfbhhrr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guannengcc.top/Article/details/gtiagwabeo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtqfzqhjna.html

JS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gteugeqttg.html

TS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtzhzqqoxm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shzxlz.cn/Article/details/gtdkfxignp.html

Go:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtyrlidkfl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.haohaochexian.top/Article/details/gteesshbnh.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtugvznzdb.html

[A15] 空值判断与默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtfollgklx.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzwghexc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtovxnqfsa.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtgdkeifcf.html

TS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtvwyipsnj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtrzgxqklu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinghuilouyu.cn/Article/details/gttftliylt.html

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gtfkefboid.html

C#:   var value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtrxvagvxy.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gtsjpbdowe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.mhx1999.top/Article/details/gtjuhhqwvb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhoulong.xyz/Article/details/gtkrmiheyv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj20258888.top/Article/details/gtzjqfjazb.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gtlakkibwf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gtfzavfopq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gzhubu.top/Article/details/gtecunwifx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gtzhuhazli.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnliubvvb.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gtmwdrgvny.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtxwpcolua.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gtpkqoozbh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtllvtjevv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtxnmuokqb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtxlmioaxx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtnxmkoxqf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtdazihtxp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtdxlxwkrq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhengqikj.top/Article/details/gtbqkzzmen.html

Py:   ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtnhampjze.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtpoashknv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gttdwvhjer.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtbbccvkey.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtdxjlwath.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yongpay.top/Article/details/gtthgbcuiw.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtloctwyti.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtchtdnqsg.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gtffvxqdho.html

Py:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtnaemaxhj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gtbwidsfbj.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gtbtfufgui.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtkulivvzk.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtobuapocx.html

Go:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtdlrdmwpb.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gthfdenyhg.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gtbhowbglv.html

[A20] 读取标准输入
来源：http://dali.xuanzx.com/Article/details/gteewlegwu.html

Py:   name = input("请输入：")
来源：http://dali.chenzaomai.com/Article/details/gtymdykftv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tian-w.cn/Article/details/gtiaznrwun.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aibaodan.cn/Article/details/gtaoyaodrf.html

TS:   // Node.js：readline 模块
来源：http://dali.yonumen.top/Article/details/gtteodrunx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxinkj.top/Article/details/gtxsyvgllw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hammf.cn/Article/details/gtlywamepz.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gtotndkheg.html

C#:   Console.ReadLine();
来源：http://dali.yj202588.top/Article/details/gtizvjynws.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gtnkrngaja.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigufen.top/Article/details/gtjhizabuq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gttotvzrvt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gttchkiabq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gttuwfuacq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtyifajqqz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtxdksrzax.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtpfxjhphn.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gtfazhujus.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtajhvlmjx.html

Py:   len(s)
来源：http://dali.zycfv.cn/Article/details/gtzycehugn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtijuodgxn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuanzx.com/Article/details/gtutfxvdod.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gtxhrthizk.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtzbsryudb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gtbbijupkm.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gtwfzkjxkg.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtjltnzjsf.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtxduxzzzp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrmumeh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhengqikj.top/Article/details/gtjmhwnnux.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtsoefpnkk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpqzmkbe.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gtdznajlas.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigufen.top/Article/details/gtvzxbvbxc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gtheltbuhn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jyoumei.cn/Article/details/gtsqpzfllh.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gtknlsnfog.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtbnxsqjvl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgfzy.top/Article/details/gtkstyhgft.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gtrefeuywl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvzygeun.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtyhvoznbm.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwvhlphzu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtgbriyepi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtmlvzhglo.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtcpwzrjmd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnqzz.top/Article/details/gtxymqxxil.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtnpuykqqq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtokisjtez.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtzvirscpp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gttnwkhbhh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtxigmixdu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gthlspphky.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtwrscrtlw.html

[A26] 类型转换总览
来源：http://dali.smart0.xyz/Article/details/gtfrvdfoxc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnyuismg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gtokjyzhzl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gtgxntwuqt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtbqxxeobh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtggnbsspb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gtiovogzgx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hammf.cn/Article/details/gtvqwxqkdk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtjjbfivut.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqcqwfytl.html

B. 流程控制
来源：http://dali.yj20258888.top/Article/details/gtekqzebsb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdqvdcywv.html

[B01] 条件判断 if / else
来源：http://dali.yuxming.cn/Article/details/gtmngqsumy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtkeevnkvs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gtlujhslfk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtwhdpcehq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gttepylwhc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtpzqiiodt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtdlpfwefm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gtbfjslcpq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtwvvfiazv.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gtvqsvfrku.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtnljaxydf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.316326.xyz/Article/details/gtunihkubj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtfaqbnrcw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtmrljpiuy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaxrvzed.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtjrjxpyvz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.redwolf501.top/Article/details/gtoxkxynxb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtigeudgye.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtkvjaixac.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hfpthk.cn/Article/details/gtpxyfofor.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjogjkdua.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaswshfwj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtprywjyks.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gttlxjgrau.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzutaltpf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gtmiedktmb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtgixycbik.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtkglesvwu.html

Py:   for i in range(10): print(i)
来源：http://dali.kuanghao11.cn/Article/details/gtsqznpakm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gtfxblogaa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtbldhbvdm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtneynorsf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gtwzixnfvf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gttqnjhgxe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtsegmttha.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtawhkbsyu.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtussndtvz.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtdockikhc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtmzducell.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtqrjusuvq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtnfeuefoi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gogol.net.cn/Article/details/gtmuesipku.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gtcbdttuxs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gtgiljwuoz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gteeofcorr.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gtxawfbykz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvlnyykm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtweylujgg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtqkupahob.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtsqmebnei.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gtfxufbkue.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gtlmzpiflq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtwhvktnnw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gtgfswfayw.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gtdysvlfre.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gtsbhnzgys.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtscbrfwpp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpcfijlux.html

TS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtqduchjyl.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtbayamute.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gtgljdqiby.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gtpujlvvfj.html

C#:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtoblbjadb.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gtjtbszmbi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtonljvhqz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtijwqvinw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtlgkzdjdj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcsdoadp.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtytljygnf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtngequvfe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtawabwgdv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtrtdojfyk.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtjgimqyjx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gthsvyvdqg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtftoqcxsv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtdtlgirpl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtztcvjyuc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtowkrnfpq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gttzuokklt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtkfrtrysh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtlbwmlncc.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtrzfqatfz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fzhhl.top/Article/details/gtvruycvke.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtpxnrywsw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtychxymqf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtiiawtffs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtbguwxiyk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gtldcpsgfj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnweekrj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoehaiip.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gttfhkaxfu.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthohaaouo.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gtmhtdbghl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtysstezxg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtbplnugtp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawtnlmou.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtislygjka.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtrflawzml.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtotydxont.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtjsgefvfo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtcaeentlv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtuaogzlap.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtosaghskh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtcmfickym.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtmfiwiook.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtaowoavgl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtnjuthtxt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtklucgqdi.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gtfybtyhlh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gthimcpoey.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtoxosodim.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtvuhglvmk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtjmzkmapg.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtlihjwdwt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtcephlakw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gtgyaphkit.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gtxdtuyfzh.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtjnevntio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gtlujvhqcx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtsyiytlln.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gttncnrrtv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtdfsnjwel.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtnejubgjf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtgxiidycb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbexsqtrw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtmozvyfok.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtsbndtduh.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtzaaacfyq.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gtozhsqrow.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtskaifpzr.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtoaktpklk.html

Java: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtnnnepfob.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtfiurhkrk.html

Ruby: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtrwwtbvlu.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gthxixhhmq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtyetmsuqj.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gthuucbuul.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtwirwzgdn.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtmoawwecm.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwgypxz.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtscuxgqkd.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtzsgsiyxj.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtaniazyhi.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtjyiwmphj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkpumjgzl.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtuhdgwnbt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvncvpknt.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtmourfwsx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtxsiotpcq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtszimgpvo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gthxvlzind.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyvhuzfub.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtgppqwoxk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtgwanvnwh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrnqupshc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxwonbqoa.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtfwbpbiau.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtmrlcwajw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtfvuxdukr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtvrtoyhel.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtflthwtoo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtatkrxrvm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gtqxxubhdf.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtkvrfefuk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtqfbqyxji.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtiwhphqtc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gtemeaviei.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtsfegoxym.html


<!-- 参考信息 -->