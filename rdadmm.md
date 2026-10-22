代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhixingplan.top/Article/details/gtxoavbspj.html

JS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gtbbpszxnd.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtyfydvczi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hysaishi.cn/Article/details/gttzeftpji.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtnudvnzmo.html

Ruby: "Hello, #{name}!"
来源：http://dali.hammf.cn/Article/details/gtstsacvyw.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gtfiuakoce.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ehwqpu.com/Article/details/gteemlgnmf.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtaakbyxwx.html

PHP:  "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtswuvhiwz.html

JS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtnjfgftnp.html

TS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtxvbznfad.html

Java: "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtyriuorkv.html

Go:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtmdtqhvzi.html

Ruby: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtrahyjekh.html

C#:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtfonnzxvn.html

[A14] 注释写法
来源：http://dali.tianlin.xyz/Article/details/gtcbuoahnb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwxwiqvs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtxwaxskbq.html

JS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtalidndiq.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtxdxgitjd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tanke756.top/Article/details/gtxtsxnxez.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtdygxkivr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hywenlv.cn/Article/details/gthlxhvkhd.html

C#:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtxpfjwkzy.html

[A15] 空值判断与默认值
来源：http://dali.fzhhl.top/Article/details/gtzrvtycfe.html

Py:   value = data or "默认值"
来源：http://dali.fzhhl.top/Article/details/gtmrvavuky.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtjcjrdllw.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gttyvzwtcs.html

TS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtscarphgy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shuidangran.top/Article/details/gtangyznxl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.daxiang520.top/Article/details/gtpzuulrnx.html

Ruby: value = data || "默认值"
来源：http://dali.fzhhl.top/Article/details/gtulpbsype.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtzpiyrddo.html

[A16] 真假值判断规则
来源：http://dali.sweek.top/Article/details/gtsoepdqgg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhengqikj.top/Article/details/gtxybaxqnm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhongyouzk.top/Article/details/gtwjkybkpj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gtfznjesfh.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtdwykqjwd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gtnsgcmbci.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cqqwz.cn/Article/details/gthwmuqfvw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.meibo888.top/Article/details/gtdbuxqcdb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtxibnapqy.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gthcuxggml.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtxfgfrgzo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtwpkgwnpp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtfgrxrhnc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gthrjthoti.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtdzhhqbel.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtugulrxws.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtvxsruyae.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtpreedfwg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gtdczdppih.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtehndijud.html

PHP:  ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gtnpgnstro.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtenfbadgh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtabwrhtlr.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gtiryqlnty.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cheryme.top/Article/details/gtxvwavgdc.html

Ruby: "A".ord; 65.chr
来源：http://dali.gogol.net.cn/Article/details/gtmfrudmfn.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gthpebdfkb.html

[A19] 交换两个变量
来源：http://dali.mhx1999.top/Article/details/gtvpqbjrbp.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gthnfesncj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gtitwerijj.html

JS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gteegwijxd.html

TS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gtkasrugeg.html

Java: int t = a; a = b; b = t;
来源：http://dali.shzxlz.cn/Article/details/gtzvyrfdnw.html

Go:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtmhggkexc.html

Ruby: a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwldixjr.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258888.top/Article/details/gtpplkthda.html

[A20] 读取标准输入
来源：http://dali.xuanzx.com/Article/details/gtgqmthpes.html

Py:   name = input("请输入：")
来源：http://dali.gzhubu.top/Article/details/gtrfvzjdfu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhixingplan.top/Article/details/gtmifaksna.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cucudq.cn/Article/details/gtmrmxtjjv.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfavfbfvq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnopgopm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hysaishi.cn/Article/details/gtxmmrresk.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gtyltspjmx.html

C#:   Console.ReadLine();
来源：http://dali.nwbrower.top/Article/details/gtvfreqiba.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtnumxcxbi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gtmowiiwwb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtwmnevfwn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtjraudoig.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtizedubns.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gttkhlxuvp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtuvrkplwh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbskpsqi.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gtshzyvimu.html

[A22] 获取字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgewrwhyo.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gtzodwwqgl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gtzmztlzbh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhongyouzk.top/Article/details/gtmbuldtpb.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gttnwrdnli.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gtiszpkqpg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sxryk.cn/Article/details/gtcskcmnej.html

Ruby: s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtyyqmtznj.html

C#:   s.Length
来源：http://dali.jianghu66.top/Article/details/gtykszomrq.html

[A23] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtmcldcwao.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gtcatocwrt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sufxvd.cn/Article/details/gthxpjkwnk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtagkcflwg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtajgsedxd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtcgwbbruv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zdqjudy.top/Article/details/gtosvxemgb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtxhpasqcf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yonumen.top/Article/details/gtcdqxmeny.html

[A24] 去除首尾空白
来源：http://dali.cdnleiting.top/Article/details/gtpkunjkxz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.mhx1999.top/Article/details/gtohhgirit.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hammf.cn/Article/details/gtwgdegogv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gttschkgwf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gtmstaumqq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gtvoeqlgly.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gtwdhnxmyf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yangfankeji.com/Article/details/gtomlyecan.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtkneamgap.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtbmyybigj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gtsldyhgwd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gtujpsmeav.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtxdcljagj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnhtuaeu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtdkvdjhjk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gticmdfzux.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.mhx1999.top/Article/details/gtjmcvtzqv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtgxnucarp.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtlhadxoki.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgufenzy.top/Article/details/gtbdzqdlwg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtbwiklhqw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gtdtbswzon.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gthcfhokox.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtkglrhsrt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guowangkeji.top/Article/details/gtcnhgklst.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtjugsfyih.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtqjnivmaj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjcikjmdg.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtdehifnrd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvklabdjz.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtfnvcvrly.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gtrgzxiuvv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtyyurszpq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gttmnffokw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtddkdpcdh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtzbzvpnne.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fengsongda.top/Article/details/gtrgylxzso.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jlsjyb.cn/Article/details/gtiajmaebk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtunrnqmgk.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtzdqlkoin.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gtyrxlvvzd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dashuyun.cn/Article/details/gtgbgndurl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtbkyvppob.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqcfcijd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtsmruqhcx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtsajbltod.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gthtqrpehd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtuslobgsf.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gthmyqrwie.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.0kj1m.cn/Article/details/gtreesyzlb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtsivpcjis.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtbwavbtvg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtnobijhbo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtdhbcecgs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.meibo888.top/Article/details/gtvkraezuk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtozkzvatz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gteuhmxdum.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtfzuogfnk.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtosgjvmva.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gtzarsbynk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtdqyeiipi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtcoiogwgl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guannengcc.top/Article/details/gtndakouvx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtnplcbcdj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gtyhbnjzjy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtafjhtmkp.html

[B05] 遍历数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gthpfrxicq.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gtmlbxqvto.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gtkhyzflnd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtgmtugcoe.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtayjwkkhw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtspgqdrxf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtgaoymlvj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gtozuevjbs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gtbbkqorkz.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtqlzcpaow.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gttylohntz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gtdvwgcrps.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtzfidqfbf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtdrgsslag.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gtclkemrka.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gtwkrbpwjl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtttidwcte.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hywenlv.cn/Article/details/gtlsqsyduh.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtheufwasx.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gtswvkkycp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gttcignpfr.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtltzccimr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtyummqutj.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvudevnod.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gtwptypjsg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gttqcpwwwi.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtnrzghjuu.html

[B08] do-while（至少执行一次）
来源：http://dali.tianlin.xyz/Article/details/gtddtvzocn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtdaayfcrz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtheuotlqw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtdiwylsdn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtehxaumip.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtuvbyhikz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtdfabjkot.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtzvkpjbaz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtmxpaiyum.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gtcrhdwyig.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxjcczby.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtuyuxhuuu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtcveiwnwu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtyffrushw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtirbziqyn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtclzjacvi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shangyingyoupin.top/Article/details/gtpzclblpm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtglxvztrd.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtpmzejbxa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtosrsxxjr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfpcctfq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtjvtpbvnu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtjvqjwdqj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtpjkqzpba.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtzfwyobdf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtzpaqmurc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtomzfpnbm.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtlmbglfbn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtqedjnmyh.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtkigyzrtr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmdsytsg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtnzjugryy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzzrywgpa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtaqhquplk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtbtvbiayd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtkgfmvdjd.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrcnlhnk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtbjvvcmdg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtygzstfwr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtdbqslukp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtwwenefom.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtqezpttki.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtwzbybtjg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkuzmzog.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtngiexlyy.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtyutkxebt.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvscswfb.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtilucopxe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtqtxlpvsw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gttorgmvve.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtdwslceaq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtyigxldma.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtpwscaywu.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gtralkndwg.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gtxjmaxvhq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gthzqyeeai.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtlrromyvf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtdzfjvgnf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtnwmttfad.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtbfeisvtb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtnzbjwpjb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtssptserv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtyndyckwn.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtcehagpov.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqibjnwsq.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gthmdpjzhz.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtipilfeqf.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsbqpjqs.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtsazjftwb.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtlajcakhz.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjzrwnlq.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gttbfvnizc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtmcqtlecv.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtpigdmcsd.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtswwnqvvq.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtvjezzthm.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtnlfiderv.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtboceqspa.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtuscnucwm.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtkxkvpwyn.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtqgwtpqcj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbzaayhel.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtkshgsdfc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthkezeejp.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtxmdjtdds.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gtgtkummjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gteieofdge.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtmgdunixo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtsnrvgxls.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuckkhjik.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtkfljycvq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtletnctxc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtkvxrlswu.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtlsultzju.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtcnjytpdg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gtspofhxyo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtxuknbjlq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfzegecdr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtspegfxgt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtrtmtsnvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtuzdoyacg.html


<!-- 参考信息 -->