代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtxkaiidju.html

JS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gtuyjqumas.html

TS:   `Hello, ${name}!`
来源：http://dali.pycfn.com/Article/details/gtofaohpgr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sysykeji.top/Article/details/gtnaxnwjsj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sxryk.cn/Article/details/gtrerwwgjj.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gtwigfltcm.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gtbcwtyqiz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dianchejie.cn/Article/details/gttkotxkpv.html

Py:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtiqaqvcan.html

PHP:  "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtowhzcdqa.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtgrbqaoid.html

TS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtwpgbzjqd.html

Java: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtkbxzcvhy.html

Go:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtmwxxswpb.html

Ruby: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtriisdqrt.html

C#:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtfwhnyzhs.html

[A14] 注释写法
来源：http://dali.shzxlz.cn/Article/details/gtlvidnbvs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shangyingyoupin.top/Article/details/gtqybbegzw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtnztpwsvz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtdecdqfqd.html

TS:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtpzaibumi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yanxiufei.cn/Article/details/gtyfdsuuub.html

Go:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtrxsrpvix.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinqigufen.top/Article/details/gtjtwzmiup.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtffylscjy.html

[A15] 空值判断与默认值
来源：http://dali.hnxiangtu.top/Article/details/gtzkhzwhos.html

Py:   value = data or "默认值"
来源：http://dali.haohaochexian.top/Article/details/gtbwsmtoqo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxoscxqu.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtveustwdv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtjyclzvnm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shuidangran.top/Article/details/gtdvyoochd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gtjbufpnwg.html

Ruby: value = data || "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtgglixbag.html

C#:   var value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtthnoitdh.html

[A16] 真假值判断规则
来源：http://dali.mhx1999.top/Article/details/gtgcfzqvaf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtxljknvja.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gtxxtpeaoq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gtysklbtfq.html

TS:   if (!x) {}
来源：http://dali.xylfe.cn/Article/details/gtpatpcchh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcnbjssjh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dashuyun.cn/Article/details/gtashgcqnm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gttfrbrtxn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gthrtuikuu.html

[A17] 位运算
来源：http://dali.meibo888.top/Article/details/gtrynmkpae.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtpmktiasb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gtkrxooamy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtahgbjlmn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtouymhbnv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtsdeodqeh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gteazfavlu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtxhdxwqhr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtnztivouj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtedbcbwvi.html

Py:   ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtdctfotzg.html

PHP:  ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtiqoivrza.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtxfkpqfwh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtkterzsuz.html

Java: (int) 'A'; (char) 65
来源：http://dali.hongshengwenyu.top/Article/details/gtynelxzbj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hfpthk.cn/Article/details/gtnukgkkzv.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtpympirho.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258.top/Article/details/gtxkodwaqa.html

[A19] 交换两个变量
来源：http://dali.guowangkeji.top/Article/details/gtouflcfwe.html

Py:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtvgzukvos.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.quarkkingdee.top/Article/details/gthjatpwgv.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtnhfbtqae.html

TS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gtjkamyvzm.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258888.top/Article/details/gtsiyfyqve.html

Go:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gtcazqiobt.html

Ruby: a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgkhfkbm.html

C#:   (a, b) = (b, a);
来源：http://dali.cqqwz.cn/Article/details/gtchcnvtdi.html

[A20] 读取标准输入
来源：http://dali.hysaishi.cn/Article/details/gtzesaygfb.html

Py:   name = input("请输入：")
来源：http://dali.gaohongyu789.top/Article/details/gtisoitpka.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daxiang520.top/Article/details/gtfbtmslaw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fengsongda.top/Article/details/gtxqxvxooz.html

TS:   // Node.js：readline 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtycwghszc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shuidangran.top/Article/details/gtlqcrybiy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gthsmswrjd.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gtlhkkzrfw.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gtaukrgmeb.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gtsroejntb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzfiidnln.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtefsnafso.html

JS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtklmxrekh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtqdjkvcko.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gttmldxgxy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtfqzjbdir.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtvfucffzz.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuxming.cn/Article/details/gtpcirngon.html

[A22] 获取字符串长度
来源：http://dali.tian-w.cn/Article/details/gtnczshbhb.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtifrlxdfw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gtnyhibgxh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gtputfieps.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwluygicr.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtrmtnrojf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gtfyyolttw.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtjervsliu.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gtsgmkujsi.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtlbtfhhpu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.fzhhl.top/Article/details/gtcipkrtaj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtnmsqrcsu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtzzwwkjxy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmisgtxp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtovewxdag.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gtiinhtsti.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258.top/Article/details/gtzidvhgsq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hfpthk.cn/Article/details/gtjnwkvcow.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkodffhk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.wangdashe.top/Article/details/gtqtbxwgsq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.316326.xyz/Article/details/gtfaalglaw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gttlvaphgu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gtozuwskql.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cqqwz.cn/Article/details/gtpuzlqaba.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gtwvtfybtq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxorbvp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtfvsgyhux.html

[A25] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtniwxbvfp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gtafxoqpba.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gzhubu.top/Article/details/gtdzbqjdfz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gthknyfldw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtwbkuwgtd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtvolqiajg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtpxunmavq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gtvajcymzz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gteomntnhk.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gtwiccjwna.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gtmplmjlad.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ehwqpu.com/Article/details/gtnmkwyczt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gtwafxpdee.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtgatxnwyz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gtbhkmwtae.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gttxybsvaa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.smart0.xyz/Article/details/gtyxkxnqjd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gtuhmadcgl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkgrkunku.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gtbxzkogkj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtorpqjzeb.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtgnsgdsps.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gtswtpcckd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hfpthk.cn/Article/details/gtnnyaoihm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtgwsejdut.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtmeyjejtt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtayxlcgof.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtxrtqyomh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtxmwwvkbe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexezbdem.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtuylbvxoq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gtoyebjfnl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxydbgzrc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtemyhiijn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtjbnbqxnk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtqcqagpkf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssvrfbxz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gtmwdzplge.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtedrykzah.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwywzvtcy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gthaedufrs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtajtixmpq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtzxanhmvo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtomcpewbh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldklauuc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtqqekovui.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtybiamzlt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtdakjoaef.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtvzhgljzv.html

Py:   for i in range(10): print(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtedqkogcx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gtijpiytzo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gthprigpip.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtsgijzfrw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtmxfpjayy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gtdfldcrse.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtjzlfywwi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hfpthk.cn/Article/details/gtvpxujfay.html

[B05] 遍历数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtgpaauvgv.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gtlyukhgrc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gtvedxyoyg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtgydigqqz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtoqqmkjay.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gtyxvafhpg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtmgixsjlp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtetuukxyc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyikiqoww.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtjyldvjus.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtqxijmcrf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtxgpxinie.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gttrjncwoh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtwwgohbor.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtpbqaulhy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtgyigvgus.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gtkdbjtazp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtktsvagpv.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtmxruvfdj.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gtarzxmtgh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fengsongda.top/Article/details/gtolrcvybi.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtmldvyomv.html

TS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcqbtqaou.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtbxzcifnn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtzprfvolo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gtbkwsxzyp.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtdikhozvg.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gtndlxloph.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtxrbxtvho.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gthlbpkukz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtycgmrmpw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtujengdxu.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtrtqkckqz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtnhhipauw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtnmamvtpr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtykxgfzyp.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtbjrzdxds.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gteeuucoad.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtynlnhdrs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtnnqjqrfj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtluuydxzz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtrglquuld.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtlfebwrxi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gttuuoeewb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtkyurullh.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtuoygdlre.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtkepidjta.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gtkktyyhtu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtqdipyhbf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtdybfuxnw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtmqrtkhqk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtnqjvrddb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtqygtessk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtcbwzyaao.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtzbcdhibm.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gtgiasudze.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtczqzxpjy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtauqagksl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtugcbbyra.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gtzqowmkvt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtxjdeuxpd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gtgsycthyh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtnnzphfzo.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtikgipfbr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sufxvd.cn/Article/details/gtdvabqqlg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtwipusyuk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvlqajhj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtbkmnasog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtzonumctp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtayoowxts.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gtkihndklp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtxcefwlts.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gtxmogwwaz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtqequisxi.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtlaclvlxn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtridvalvl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtgjmtlpoj.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtawoyhqkv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtjiulpptz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtbfeusbgs.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gtkqmebgee.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtbejfuuyk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtozpkaqnh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtfyszconz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtohtuegvx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtsswsfnrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnikwugfc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gtiafrmgzy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtwrxzfvus.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtxqyemiwm.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gtzmpdnzar.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtpmcvffxj.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtjskucign.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtdtuckepf.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtertmxjpq.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtvmkabama.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtiezmrvmw.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtonudhpra.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtxtmdhced.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtzhuututz.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gteqaaxibv.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtabkaogim.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpzjtoal.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtnpqtjvze.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtupjlkrtb.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtggwfydhj.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtbmwbezjf.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtbmlrhkqh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvbvvcmiv.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtefphtreo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzgyixekw.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtluzmuxzc.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gtuidujyof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtcvwpmmmr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtosektzli.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtocpwxyvh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimsasptg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gtgqslgxpd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtqrysvcdj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpfriwirq.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtcotsdegf.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtwohpmcki.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrrdfbnll.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtrdysuddb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvzjvnra.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtilbggfjx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtqteychmx.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtbysgxswq.html


<!-- 参考信息 -->