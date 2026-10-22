代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtehiquebb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtacfwzfli.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxuanxn.top/Article/details/gtsbyttuvi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shzxlz.cn/Article/details/gtjzknnzwh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gtxzpguppg.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrgwrusi.html

TS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gtxuimpyuj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gtbueegjox.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtnaahyuuv.html

Ruby: "Hello, #{name}!"
来源：http://dali.birdmap.top/Article/details/gtxlltkzsd.html

C#:   $"Hello, {name}!"
来源：http://dali.quarkkingdee.top/Article/details/gtywvepiqg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.aibaodan.cn/Article/details/gtsruqcfjn.html

Py:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtaugfcyne.html

PHP:  "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtgkbwgjfz.html

JS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtmvadtggy.html

TS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtodawetzx.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtquolyycg.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtjxcfojnj.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtudfponuu.html

C#:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtwdfdznbn.html

[A14] 注释写法
来源：http://dali.ehwqpu.com/Article/details/gtujvvfhfj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jianghu66.top/Article/details/gtwvsvszra.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtdbybrkuh.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtmeclcqed.html

TS:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtxzoabafq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sxryk.cn/Article/details/gtqkfdpeoo.html

Go:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtotdhsxlu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtkjlmnihi.html

C#:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtbdaipvsv.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gtxtpjftoe.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gtyacwgsmv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gthytgblkr.html

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtuecmahnc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gttmyopusn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gtkxarxtdw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtovavkzuv.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtkvuryjon.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtmofsdhma.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gtoblfywwn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.316326.xyz/Article/details/gtdbnzdxbj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yangfankeji.com/Article/details/gtczuxiqrj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gtihnsfypj.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjjtjsdpg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtexnkqqhd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.haohaochexian.top/Article/details/gtdhyyapaw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhfhjnye.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtjqhdblce.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gtpyyvooko.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtiaiemonw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtymnoozwu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtwiygpxgk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtlovmjprd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtvultfghc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtcypffzje.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtqpclycuy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtbufdtfkp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cucudq.cn/Article/details/gtchdybejo.html

Py:   ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gtxrxrwpsc.html

PHP:  ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gtrrurtfmo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yvedp.cn/Article/details/gtgudmgzeb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtwytcqyfv.html

Java: (int) 'A'; (char) 65
来源：http://dali.xinyue.icu/Article/details/gtgbqhomuu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gteatgimlw.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxuanxn.top/Article/details/gtqtadnxax.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxinkj.top/Article/details/gtpdfiapjo.html

[A19] 交换两个变量
来源：http://dali.cashguo.top/Article/details/gtcjyklpze.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxsrvnku.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenzaomai.com/Article/details/gtugcsvixn.html

JS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gtgvhbzabp.html

TS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gthizzfegl.html

Java: int t = a; a = b; b = t;
来源：http://dali.zdqjudy.top/Article/details/gtgzzhlibm.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtiizvxeza.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gtlmdbvswv.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gtxulumzey.html

[A20] 读取标准输入
来源：http://dali.meibo888.top/Article/details/gtpsvzxvhs.html

Py:   name = input("请输入：")
来源：http://dali.dashuyun.cn/Article/details/gtigsymjua.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxinkj.top/Article/details/gttajpueax.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yvedp.cn/Article/details/gtclyfxqxp.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gtscdmukte.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gtymjgfipf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxinkj.top/Article/details/gtzxxmdhxh.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gtbqlvxwyq.html

C#:   Console.ReadLine();
来源：http://dali.jinqigfzy.top/Article/details/gtwagvyxdo.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gtoulhdhaf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gtagzbkwwb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gttliunwzc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtuxamltxx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuyifuzrs.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtgeexvuam.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtqdoupbmi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtxjqlkbmu.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gtvlnttfkc.html

[A22] 获取字符串长度
来源：http://dali.cashguo.top/Article/details/gtoboetkhq.html

Py:   len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnefikjpr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gtuphwwntp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gtpseojdly.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gteuecgyti.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtmmpsffcb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtudpvujtj.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtixjoopae.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gtwmnfrwro.html

[A23] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtdigugkta.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gotoacloud.top/Article/details/gtvuphvyfj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.0kj1m.cn/Article/details/gtmhdpgdpe.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtxutcabgi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtascfzeqa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gtncazcodx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hfpthk.cn/Article/details/gtdzqcbgud.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtyjwxzcww.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gtsfvqkudw.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gtziclybyl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gtrnowjyyl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gtkgeywlzt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtdpavblma.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gthpwyqsqi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gtkqydfbjc.html

Go:   strings.TrimSpace(s)
来源：http://dali.cucudq.cn/Article/details/gtkfwdipdb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gteitqyfld.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtocquvbzs.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gttucmucji.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tanke756.top/Article/details/gtsfzijkvt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.redwolf501.top/Article/details/gtmcthipgh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtnyyljlcg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtfdhyvegi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtdcjuixwd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtyowchzbx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shangyingyoupin.top/Article/details/gthjzzcizn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtwnjtgvvh.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtyonqwosg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtubslxbus.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjctuxii.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.havefunace.top/Article/details/gtjchdpewm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gtezcldocw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtaaiafesh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gtdszxenlz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxprxhvf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtgkvtozct.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtoqjpcked.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gtsvklixvg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthpizvuad.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gtsxupntss.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtbtdozfpy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gtbsstswal.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtzxrisrwk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtrbxkkwjb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtmsdfgjlb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtnlfaufof.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkngweoiw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtshetbiry.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gtoajsziee.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.haohaochexian.top/Article/details/gtfqdplnor.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gteyzuuqyy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtblieinbr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtjrfchbuz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtqpkpshxm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gthgfaxfdj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gturetrlrc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtaxanokak.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gtekhwkxty.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtagaggrnl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtgnvijnwh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtpgmvcyyn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrqldewj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtzbwllpdf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcxnhcob.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gthttdyinv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtimpdzsgs.html

[B04] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gttnrcuzxp.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gtjewtqohv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtfiuykeby.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtittghgrw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtjhvwdfnx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xylfe.cn/Article/details/gtherszbpp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shuidangran.top/Article/details/gtbaxwekol.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gtakcbpmgv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtxpfazawu.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtsooxhhlj.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuruorce.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlggjunzu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtuaqoukbp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtmpvngveh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gtquzfeogo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sysykeji.top/Article/details/gtcogifyxw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gtyhahmhdg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.aibaodan.cn/Article/details/gtayjtrckk.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gtntfytess.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gtipjmhkev.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gogol.net.cn/Article/details/gtpczfugbj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliyqrjpr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtjadupshn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gthxhetcae.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxdflwxo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtynlcupbu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gtchhnzycu.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtgdbydcjo.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtklbimvuz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcipslwwv.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtjbkzcvho.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmmrndhfy.html

Java: while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtiokcmywh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gtvddayxww.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtdsdcwphv.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwquyemmt.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gtgdgfignp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtcomqpkfh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtdmuvsmik.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtcxiqahqn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtowylmdfm.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtpugqekai.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtlsyaobbz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtnulxeakk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtuwtmmcsl.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtwtfwusze.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gtybbkiufd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtskdrmcdf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtnzifhcls.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgfrwrjnv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtstdkgqyu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtyfjclfjz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gttkxoftqy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtoagjtwmn.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gttdutuuwy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtusllcagd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gttkyprbfg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtzkkhdowq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gttbbkrmqy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtqsayazpz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtkjfdkcsp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gtvrjgyqke.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gttzbncrjm.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtdwhyitsb.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtnmhaiwof.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gtlwmyduyo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtmjgyobxn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtifbauems.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gtwbwhvjed.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gtxrgkzuwp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtijawmgwu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gtlbupfgis.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtgwtdrqqr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gtsdahyakd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtyqpugoek.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtesbsrsfb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtnqvkxynj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtpipathqm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnbyzfug.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtvnhomyxc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtgoxrocny.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtjmjafbgc.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtxpszqybh.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttymlwxyj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtkawcqonu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtsabwfuss.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquijghqv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynxjajiy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtlyzgmyoe.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtwfucsogq.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtirhfjhkf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtlcqjtgrm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtaqwkzdtp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqblxfllm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkwrwojgk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtmupopqnh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtmjmxsgxg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtiaelghqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtjgpuyagh.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtxvmscjaq.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gttjlfoeof.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtyvsbctfn.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtqdaahwfk.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtlrgagzxz.html

Java: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtqnvcouub.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtryndvyfa.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtiivytozh.html

C#:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtojvsikon.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtdilhvnfd.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtodmakmow.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtqiibooxr.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtrpoiaxfc.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedcrzque.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtjtliagwn.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtmlhqudmp.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtolqclbka.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtnusctkzz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkgyxoopz.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gtwtdvlxzc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpnzdccko.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkabdxebg.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtyboskajf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtulbshuto.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtcduovyyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtezhxqfxh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtylpcpqbw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtwociezua.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtyphoqrxj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtngisgskc.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtrsiuomtb.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gttjmkahtt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtqofwurja.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtbarmokiz.html


<!-- 参考信息 -->