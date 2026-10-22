代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtsermlgcn.html

Ruby: "Hello, #{name}!"
来源：http://dali.fzhhl.top/Article/details/gtwhpajhfj.html

C#:   $"Hello, {name}!"
来源：http://dali.daxiang520.top/Article/details/gtwflukykb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevtbxjnq.html

Py:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtplnnbqbe.html

PHP:  "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtgviscfav.html

JS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gthesqefbb.html

TS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtqbhxfgsu.html

Java: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtnkzihlpw.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtlnaafwwe.html

Ruby: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtkuehptgc.html

C#:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtunackykp.html

[A14] 注释写法
来源：http://dali.jinqigfzy.top/Article/details/gtrgdgimpm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpifbptq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtjqhspeqs.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtoxqzicfq.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtqapjbpdk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gtmtpqiukk.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtmstzneuj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hysaishi.cn/Article/details/gthbxmbvdo.html

C#:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtbcwobspp.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gticbkukmo.html

Py:   value = data or "默认值"
来源：http://dali.sysykeji.top/Article/details/gthyigqlki.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gtlbsyrftb.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtudmmjgnr.html

TS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtdzbklcka.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigfzy.top/Article/details/gtyglmhnsr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcnzdilz.html

Ruby: value = data || "默认值"
来源：http://dali.gotoacloud.top/Article/details/gtczzkuhbd.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtgwqzsqos.html

[A16] 真假值判断规则
来源：http://dali.pycfn.com/Article/details/gtjrwdsgeu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.316326.xyz/Article/details/gthiftalhg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gtnuvgdwjw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gtkkwmlswz.html

TS:   if (!x) {}
来源：http://dali.aibaodan.cn/Article/details/gtzvxezmsy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xziqi.cn/Article/details/gtusmndcyn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gtmktywmaq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtwismdlcg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj202588.top/Article/details/gtxuwyvoig.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gtbrxmntgk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtaountyfq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258888.top/Article/details/gtklagulcf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxptvtbb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtqtdzzxgj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtnehbreer.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtwavuyqim.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtywipzwlv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtyyagfoma.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gtzxviyvti.html

Py:   ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gtifakdcjl.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtfqxdkefv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtxplulyur.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gtlqgvnmgj.html

Java: (int) 'A'; (char) 65
来源：http://dali.wangshuangyany.cn/Article/details/gtpozwqqjx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangshuangyany.cn/Article/details/gtxdmeqero.html

Ruby: "A".ord; 65.chr
来源：http://dali.hammf.cn/Article/details/gtnfmuquqq.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxuanxn.top/Article/details/gtrqfeczwr.html

[A19] 交换两个变量
来源：http://dali.aizwys.cn/Article/details/gtmlalmsni.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtzauyutbu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.feifeiyinyue.top/Article/details/gtiqwzxysk.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtfqfwyddf.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtpxgmzgbz.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenjidiqi.icu/Article/details/gtprsojtzz.html

Go:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtfiqvlgeq.html

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtpvmkutzh.html

C#:   (a, b) = (b, a);
来源：http://dali.jlsjyb.cn/Article/details/gtwbybeurl.html

[A20] 读取标准输入
来源：http://dali.c1oappe.top/Article/details/gtuyslsayt.html

Py:   name = input("请输入：")
来源：http://dali.hongshengwenyu.top/Article/details/gtmymdsxmm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gtscptbfxt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gtjenyfkwn.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gtvunvicwu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gtojfsyaic.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuanzhike.top/Article/details/gthliuzgmd.html

Ruby: gets.chomp
来源：http://dali.jlsjyb.cn/Article/details/gtoopkbtuo.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gtbtuzdkcl.html

[A21] 保留指定小数位输出
来源：http://dali.shuidangran.top/Article/details/gtgtpchwco.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hfpthk.cn/Article/details/gtwzhspuul.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtbasqgykf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtnrijcwtj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtodeznxca.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtyfxlqxqk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtpqqtziyo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtltzidywr.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenlongwang.top/Article/details/gtchvoiydv.html

[A22] 获取字符串长度
来源：http://dali.yvedp.cn/Article/details/gtrnxttlgm.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtnzvgumjd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggahnxuj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.c1oappe.top/Article/details/gtogrkadii.html

TS:   s.length
来源：http://dali.yueranfly.top/Article/details/gtjlsdpxwy.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtstqrlwfa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sxryk.cn/Article/details/gtgjjdbafx.html

Ruby: s.length
来源：http://dali.yj20258.top/Article/details/gtjcymczmg.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gtklpfaael.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtthjarjwo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenzaomai.com/Article/details/gtoqqwqzji.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shzxlz.cn/Article/details/gtrzvnmdah.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtizkrzrhm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtgbjbzdeg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtmavqohwl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shzxlz.cn/Article/details/gtmbfalugi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtxnxqjaet.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fengsongda.top/Article/details/gtgooxylru.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtwurplafe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gtwdsxfhqb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtkkdjrvxh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtwacudiwg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtyegvlgse.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gtburpazyu.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtiopmgnuz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gtgyrwbfne.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtugnmcwzi.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtefkkyewr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gtmcfxxvsy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhengqikj.top/Article/details/gtglwgsstg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtzgpvumwk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtokdjjcto.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtvuobodpc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtugahvcrw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtncalbfmq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtakhhaihu.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtkhihtwyq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtauclhjke.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gtkckwpwqd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwatqlvmg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gtjckzebfw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gthknmyurx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gtpxxgojct.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuxming.cn/Article/details/gtibfoqnfs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtkgkoryvy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtktlnidii.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gtitzvscal.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmjgugcfi.html

[B01] 条件判断 if / else
来源：http://dali.sysykeji.top/Article/details/gtuxnghneq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gtgawshefr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtuhqnjqpa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtemhhkafj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbatwivtd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtaextiuhc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtjojmgzqu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gtsgxwdxsl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtgwazidcg.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtghrfesfd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtalfdqfih.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ydzc1.top/Article/details/gtqposdpxy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtojduowpg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtpaxidstb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtsfyqfyfa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtomujnkou.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gtmujhaggt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtwstnyfxv.html

[B03] switch / match / case
来源：http://dali.xuanzx.com/Article/details/gtxftpdsmh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxoigzth.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbmqlnjkw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtgqwrhvxy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtpwnnbfvw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmwjrlpug.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xylfe.cn/Article/details/gtbtrfucrb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtbqfnccpi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtrvprcfqk.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gteekkenxa.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gthwmkydos.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gtbncqgiyc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtlidbfpuk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvmsuvow.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gtyaykjtlu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gtzhygdlzc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtnxbmwupd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gtyyelmnbk.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtncgqbfat.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtkrmhlkts.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gtwgvlrfly.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvprshtz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtmlrmcokp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.9152youxi.cn/Article/details/gtmjuvvjef.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gtjlztyahy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtujtqmicw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gtzmnjyvqk.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtookdsptr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtfwbdlcoz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtslkamyyw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gttqtnkjgk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtycrhncku.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gtklraifus.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtpnbrthqa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtyavrbrhr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtrzbbuuoh.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtskdbopda.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtbdvgieqt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gttdkctitg.html

JS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtbbxqqsle.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtwgtpdawx.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtciicsvnj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gtdzyewnoe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gtlvtooulj.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtciavhmkf.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gthijiamoe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtbeevslbg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzesokgss.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtiakqovdq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtkgquibmy.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtoroqbako.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daria6918.cn/Article/details/gtfkzdyukf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gtcnvwtgdm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtpbplnfwh.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtqpdhonhs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtaidnkikl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtdqvnkryn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtkculeirn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtccyvubrb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtffsieivf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gtntpuactm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtkgtmldnr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtcsuwwaba.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtcxdxodci.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtcnyzmarf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtrugrhmjr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtmyyzrzbu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gtqanwiumi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtzsyddsac.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtwyfgphum.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtrtmyjxzq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtbzfnvesj.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtqyrxxpob.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtvfgromsc.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtlbysvinb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtvsbubtcb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtikjajcge.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtardwpves.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtimkcectb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnxiangtu.top/Article/details/gtbzcxpsur.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtpyqtfkpr.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuprygek.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtwzsoeirc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtexorszaa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtbhjmqwcy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtwawrjyta.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtrdxjjfkf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtrvohxrfa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigufen.top/Article/details/gtbnndrrzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtcaipwmyd.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gtbkxkhqzs.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtntaosfgx.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsflxdxsf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtwwhulxbz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gteclytbfy.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtiecxjism.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtdferklmg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtfbhluymk.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gtsolhlxiu.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtcfuzdrrk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gttmjhtcoq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtuwsjxgjf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvvmdfipp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtatnnzwtb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gtjsdqhaqw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gtiybpyayg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gthhwmxzdw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtlmhodkrw.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtycajidpj.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtfaphfxtc.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtfxxypgmu.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtiwwhrwel.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaslipjgt.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtoperypgd.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gttxqtwecn.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtncayiroz.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtdcoozqhq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtcfgdyulv.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gttcmnoyqg.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtboedyrcj.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtnhkevfbx.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtxfhptghw.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtjopmqghh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtvuupvhft.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtzsauqwtx.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtetfsogeb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoiweyxwn.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtoppdkchp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcdukwzww.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtguvyoteh.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtxmcwselw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjahwskry.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtenylishe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtvqygdixl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtghfebapf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtjkkymcqv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtzxsgvbcf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtkbycsxuz.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtjuaptdgu.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtsepaldqf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtemvedurg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtpjaucyno.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtinrynail.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gturpqlepa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gthhfzgeke.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtlsxvgkwl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtcqcspmyy.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtxpnuupnl.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtbgdxjqnm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtftugxaqs.html


<!-- 参考信息 -->