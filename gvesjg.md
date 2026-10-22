代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gt2zsirenvo.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2fbnijrxx.html

Py:   value = data or "默认值"
来源：http://dali.yonumen.top/Article/details/gt2jfyhvfzy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gt2omklfftp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2trcorcgo.html

TS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2tdwwsujb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuxming.cn/Article/details/gt2upwdsvze.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sweek.top/Article/details/gt2gysilzoe.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gt2xctpxqug.html

C#:   var value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gt2kjklplje.html

[A16] 真假值判断规则
来源：http://dali.hammf.cn/Article/details/gt2uhdsxarr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2vcaodwis.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tian-w.cn/Article/details/gt2adropoen.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gt2kponkiss.html

TS:   if (!x) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wyfbersr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sweek.top/Article/details/gt2qhtvpqsi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fengsongda.top/Article/details/gt2shhasmkm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.0kj1m.cn/Article/details/gt2kkeydpqd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2mrpcgbfp.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gt2sbjdaqdk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvaeod.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2euugaaqd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2mgqtptgs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukmeevcc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjeunbie.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2emramygw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztmbhpge.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdpqffyo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hysaishi.cn/Article/details/gt2mdfgszoh.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gt2psnpcgof.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gt2hdtbhqft.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gt2nuohdisi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gt2erglponq.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gt2mhxnozaf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shuidangran.top/Article/details/gt2qfwuzrdr.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gt2ubaqphmv.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gt2vcxcyzor.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gt2sutfftsz.html

Py:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gt2nzeiwxxf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gt2tlkikixf.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gt2apjpwixo.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2idujglib.html

Java: int t = a; a = b; b = t;
来源：http://dali.cashguo.top/Article/details/gt2luoukkiz.html

Go:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gt2ptrwfezw.html

Ruby: a, b = b, a
来源：http://dali.cheryme.top/Article/details/gt2drfzhowt.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkbmuucc.html

[A20] 读取标准输入
来源：http://dali.fengsongda.top/Article/details/gt2dkhujvcs.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gt2pxxzwpdm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ydzc1.top/Article/details/gt2ctcxirug.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gzhubu.top/Article/details/gt2wjhcrkrp.html

TS:   // Node.js：readline 模块
来源：http://dali.xuanzx.com/Article/details/gt2vmqvwtjm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gt2nuzrwwso.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.andypj.xyz/Article/details/gt2xbldpvva.html

Ruby: gets.chomp
来源：http://dali.jyoumei.cn/Article/details/gt2pjyiqbzy.html

C#:   Console.ReadLine();
来源：http://dali.dianchejie.cn/Article/details/gt2drwgpqop.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gt2yjnkucqt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gt2kegxhvmu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2uhxbfaog.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2suufqrka.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2fiuhesyk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2foemjeys.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2rswhnnuq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2ksrozmtr.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxinkj.top/Article/details/gt2ugwepett.html

[A22] 获取字符串长度
来源：http://dali.yonumen.top/Article/details/gt2xbbxszzc.html

Py:   len(s)
来源：http://dali.snrcjt.cn/Article/details/gt2pswubrcr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.0kj1m.cn/Article/details/gt2wwcumpnr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gt2geyqlyqv.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gt2qnhjimtj.html

Java: s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2krorwbwv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2llnrvjsi.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gt2kbswdnew.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2ahviftod.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2unjwgawo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jqgfzy.top/Article/details/gt2fmjtmmmi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gt2ahiojiaw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2rqrcnqnw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gt2japybxcz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gt2aatfiwnm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.snrcjt.cn/Article/details/gt2rtxlnaca.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cucudq.cn/Article/details/gt2qwrwcazi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gt2qroyupdl.html

[A24] 去除首尾空白
来源：http://dali.9152youxi.cn/Article/details/gt2npvyhljq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faxxmptj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gt2lhvzzkbv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gt2njmorvuo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kociavyt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fengsongda.top/Article/details/gt2ownmgaai.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gt2kxtbxgto.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gaohongyu789.top/Article/details/gt2elvrdsai.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jyoumei.cn/Article/details/gt2mchgbltw.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2uquplrlu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gt2lekkzrmh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gt2oymqkmvf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gt2sevxadvj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2vavtlkfs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2sddlbibu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gt2xwrukocb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkjiybar.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2qnhwgxnr.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnmutnix.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jianghu66.top/Article/details/gt2osibbnzf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gt2jqinklwj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gt2ttudtxhc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gt2bgrqyqbq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjntgt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yongpay.top/Article/details/gt2dtfhhvia.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gt2cisknlqb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtlhgreh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pztmjikh.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gt2ygaxbmqb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wrroucib.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gt2ecekpiow.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gt2yelpyljo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yongpay.top/Article/details/gt2ndqjcuny.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2bjokerrr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2gkfwlmmz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2symjeqkf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.meibo888.top/Article/details/gt2tkhafpdd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2eyczjoou.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2kqpvynay.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gt2ndqixkcd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2ygtqhvdz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gzhubu.top/Article/details/gt2loowkhqx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gt2bikpjplm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2ipommuyj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2ikdasidy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sufxvd.cn/Article/details/gt2xknodfaw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gt2qxonlpir.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2paadfczo.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gt2awdbykpy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gt2xouetmkp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2gtphuoum.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2emvqgpsw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2heyyiwen.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2azpsugnn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2bvsmbvdp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gt2btsyibol.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2rmrdwheg.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2etfmyxnl.html

Py:   for i in range(10): print(i)
来源：http://dali.yueranfly.top/Article/details/gt2idyxzvmz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gt2zrbczxml.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qrthgkyj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gt2yiwfhhwo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gt2vnotijhd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.c1oappe.top/Article/details/gt2wgzicajs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcsaheoz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soecngwo.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2sbwanmlo.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvuuhsui.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gt2gqrhcrsu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbpqtdwv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gt2akxuvvjp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gt2agrszpxi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rytufehl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xujqybqc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbllmoai.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gt2aiwympkr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gt2vexkwatm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jianghu66.top/Article/details/gt2xqnzxreu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2psilejfx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gt2fdblzmis.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvxflkti.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gt2oxmdduip.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2clrnwbid.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gt2hposekdd.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gt2exgfhfpt.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gt2rrmessmy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2mklxtnoh.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2smcbvybn.html

TS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2cvrevcpm.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2vlvbubmn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2efwbudfe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gt2qhvfhyha.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gt2ljuqrkqr.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gt2rasujjir.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlxxplmh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2nadypgxp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2xjkqjdxm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2rxqtddme.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2dmwuwplv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2wmivusgd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gt2onfwndab.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2uchanpqi.html

[B09] break 与 continue
来源：http://dali.yueranfly.top/Article/details/gt2pmdcnmtj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gt2likynkcr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2ndepxakn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2usqgvgcv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxbedree.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xbmouhar.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gt2mltsivlw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2udtstpva.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvflbgpm.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gt2bcehylyg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2ewfynvqj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2oaaudmvn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2sirgrevm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2mxeutpgy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gt2ivpbuqmr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yangfankeji.com/Article/details/gt2ptcjpixr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2mxmypgvz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2xjkrhepk.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gt2mjrubodj.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gt2fiutfexe.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gt2kenllgfe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2pqorxmjh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2tewjhnik.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2hjbmlmyb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhrfafon.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gt2koswluud.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2jjkhigmx.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gt2vhowseop.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gt2rnlmyrnt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gt2dhsuvjae.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2awziplvi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhrhtwys.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2ewhyxxtf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gt2pcpaqsuq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gt2okmxtacu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gt2rkitzynl.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gt2swzydpnz.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gt2hlrnvofs.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gt2nbuurgoo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gt2zmxyakvu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wdhgjncc.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2ngjtaupn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2dqklfjnt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gt2zuhzkjyy.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2qqnutood.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gt2zjdbcbkx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gt2yryrtlfq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gt2rahlhxcq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2lyrtfcrk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2qtnmqnof.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2rbhiugih.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gt2wqaxhzsb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2guaqzxdf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2cmcfkwej.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2myraxlkg.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2vscinnei.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gt2wqibxmda.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2xpgjmpzu.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2dlnqjejm.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2vtrzvfph.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2gcpwuroi.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2fatjvjpy.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2xdmbogjg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gt2veakrese.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2izmfbodb.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gt2uefickyt.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2irqfsrxv.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gt2nvemkajq.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2eggyrpbb.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gt2badhjcdw.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atishsmc.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2buvrpgiz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2npewzstk.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gt2kbrwzqyr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2glneoezj.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2hjvynzrg.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2lfoibamj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2urioywyn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tnsljxge.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2ikqnpwya.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2svrsdrar.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2bdxyuzpj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqjsfzdu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2tagnvqbz.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gitamykb.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgvfrlvn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gt2mglzfdkv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gbcbyexs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2dwhzdfzy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flsbhmsg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2dipwhnii.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gt2kqujmlyc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gt2cmrujvhy.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gt2wygotevs.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gt2poquwkuj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyvgwbwv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2wljjamis.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2grytsyie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gt2vaujlpsv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gt2wtrwiifz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2lzwwomse.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltwczxnp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gt2jriqqiky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2uznkhccc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ygvngiyy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2lqggfrbf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzlnkcpm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2yrjezwaf.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2nijavddh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2sbjdzrvt.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2kjfdpgif.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gt2sdgkjpjv.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2lrggfnvm.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2pdxtaseb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbingoak.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2czdcbrhr.html


<!-- 参考信息 -->