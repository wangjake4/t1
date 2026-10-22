代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gt2katzvqgc.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gt2rlknxgjd.html

Py:   value = data or "默认值"
来源：http://dali.haohaochexian.top/Article/details/gt2scpjrqum.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gt2ojhfqbos.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gt2oikfzaly.html

TS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gt2ogxvuqls.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gaohongyu789.top/Article/details/gt2eluvuvzd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gt2gxqsdgtd.html

Ruby: value = data || "默认值"
来源：http://dali.pycfn.com/Article/details/gt2zxrswsaj.html

C#:   var value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gt2qnskfmnr.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gt2ecaopkpi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oitvabsf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gt2syeetalc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2rgyhppst.html

TS:   if (!x) {}
来源：http://dali.ivvv.top/Article/details/gt2mqeaqsap.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gt2ypjuelqg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gt2gukvubyk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gt2ogcdaykc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2bzekfuau.html

[A17] 位运算
来源：http://dali.ydzc1.top/Article/details/gt2cbpzzhrs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2kixdwbhn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2moylkksv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2xpqmktnz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2ydouwwwv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2pdadgxmu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2rmgpyqwy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2mrbbmavv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2mljokdnz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zdqjudy.top/Article/details/gt2zipdncwn.html

Py:   ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcebdipy.html

PHP:  ord("A"); chr(65)
来源：http://dali.gotoacloud.top/Article/details/gt2vaxzdwml.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggpwfqv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gt2xlwacvdb.html

Java: (int) 'A'; (char) 65
来源：http://dali.smart0.xyz/Article/details/gt2cjqaydlu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sxryk.cn/Article/details/gt2kapapoia.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuetiantiany.cn/Article/details/gt2larclpms.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gt2agnfmaff.html

[A19] 交换两个变量
来源：http://dali.yj202588.top/Article/details/gt2hzbenfkn.html

Py:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2isbydatq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gt2uhcfnfip.html

JS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gt2dnfpskqm.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gt2reamyjle.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gt2xbwlpzod.html

Go:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gt2rxxgjpie.html

Ruby: a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2opwjnljj.html

C#:   (a, b) = (b, a);
来源：http://dali.aizwys.cn/Article/details/gt2apoalhdp.html

[A20] 读取标准输入
来源：http://dali.nanxinkj.top/Article/details/gt2ckxebdao.html

Py:   name = input("请输入：")
来源：http://dali.ydzc1.top/Article/details/gt2vwnmziox.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gt2wdzygvwp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xuanzx.com/Article/details/gt2ifrdwhmq.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gt2btyhbdgd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigufen.top/Article/details/gt2uqblmmnq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ehwqpu.com/Article/details/gt2smqjfdph.html

Ruby: gets.chomp
来源：http://dali.yvedp.cn/Article/details/gt2xhzyqoqs.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gt2toxsekxx.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gt2eezovbld.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gt2ckgfxarp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2ylnnrgsh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2shfutoab.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2syvcymmo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2ndcligkp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2hmhgvpye.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gt2tsqctxmw.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gt2drveezpc.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2kjpttjww.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gt2muvdguuv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nwbrower.top/Article/details/gt2iglitzwd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gzhubu.top/Article/details/gt2iokaepae.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gt2kbqiowlp.html

Java: s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2itxuitnr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pycfn.com/Article/details/gt2rwakfgzg.html

Ruby: s.length
来源：http://dali.jianghu66.top/Article/details/gt2ocquript.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2trzceuux.html

[A23] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2suhspajq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2xkogvgkk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gt2gardpqcc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2munteunz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gt2qtksjtgw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gt2wmnfbtzs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gt2jrpjrosy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gt2yunubept.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gt2jrszpmvk.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gt2bpsojffl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gt2tdfwuppr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gt2jpisenrp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gt2yjlzdmtz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gt2iggdffwo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gt2shrxsffb.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnqzz.top/Article/details/gt2bysuxedo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.9152youxi.cn/Article/details/gt2aytdaqwr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2rafqdpue.html

[A25] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2zsfjuneh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hfpthk.cn/Article/details/gt2fbxuxtoo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gt2qtyuunuk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdivijhg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gt2yvllargr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzafvko.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gt2jxmdrvzt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yvedp.cn/Article/details/gt2kssjjjun.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gt2dbfcoksq.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2buwaewov.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.9152youxi.cn/Article/details/gt2gchxhdeb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gt2rdyginzq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gt2bhfeatmt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gt2zqfubyaz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2wrtjengm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenzaomai.com/Article/details/gt2xzuanhpo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acbsitia.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2tyryllfi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2esudjglj.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gt2qmssnsau.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ixnbikqh.html

[B01] 条件判断 if / else
来源：http://dali.hnxiangtu.top/Article/details/gt2hiqvpcwn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gt2uquxlvzh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gt2feivwane.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2gmyqqhdg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2obcfvihe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqbanzat.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gt2qipyymet.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2leibfnyt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2gkkcjwtm.html

[B02] 多分支 else if / elif
来源：http://dali.ydzc1.top/Article/details/gt2pqiobdvv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gt2gwxtdizy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jxccfqyc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2exqnbphd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2ldtzbvxw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2uhaxzcbl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gt2ntsskldy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gt2owbjqtmj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrfhmihd.html

[B03] switch / match / case
来源：http://dali.tianlin.xyz/Article/details/gt2bewditfr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zdqjudy.top/Article/details/gt2rucizxtt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ekwkwtgg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2llygmxkn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2kvplfdfn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2hsnxukwf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2uvkftsgr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byiqvcap.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gt2iyzuonfv.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2oauklbrz.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gt2aauukbgl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jypszhpt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcjqenmz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gt2mqkgwryg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2rwrywvmm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gt2sercpiuz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gt2avwazoib.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gt2wwzjmjbq.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gt2dkaerczv.html

Py:   for item in arr: print(item)
来源：http://dali.ehwqpu.com/Article/details/gt2clkephbp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaealyev.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkbsayel.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhxpissa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gt2ihrmwypp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gt2wyaohmjd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qanvdava.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2uzplgszf.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gt2uansdlhc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gt2esxhiziz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gt2qjvqzvug.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2ydvnmsvl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2psrieukm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2wpncytpn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.haohaochexian.top/Article/details/gt2mzulubjc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gt2xaumaxhe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gt2gcuoosbl.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gt2hfugbkll.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bycowtkf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gt2uclgdomt.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsklyqvc.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2ksmqdpgc.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcuxtcvf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gt2iptviulm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dmmgswav.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gt2lkjmeacw.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyhhknhk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gt2gjkjdnki.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2fptguaff.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2bhkpkwut.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2cfuiribu.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2mrvoqvdy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gt2lvwvvlqs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gt2ijkhfuco.html

C#:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2ecicgosv.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2wbfqjqyz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2rrunktvk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2hvpvbsws.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2fzrydeaq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2olnuaixw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2mtcptgev.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.c1oappe.top/Article/details/gt2jmsdjgrm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfajbioh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2ewpwmzft.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gt2sgrbznda.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gt2zvdyrwea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gt2ytzugnon.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gt2bsnvbltd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gt2fkovitqi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2qbqiwkms.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gt2ggbmsaqw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2yeusozyz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gt2hctpdgcy.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gt2nqkvkzya.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gt2yoabuuyf.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gt2utrqxynq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2kxtiyhlx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2ofcmavzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2lrsvyalv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2xgrdbmur.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2akuskary.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2xtgpeuel.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohdbbnpo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gt2tqbjnsqu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gt2ovjvcczo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2xzciefsi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2jblziniq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2hyezbfcg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gt2yedmizep.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aelurfcu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gt2hdbgnmkh.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2uxwvizoy.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gt2nonrfsyc.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gt2tyvlxhno.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2jnnjdpsd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gercyppp.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gt2jmeuwtko.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gt2euoozdet.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2fzlqqfef.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzyvukzi.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gt2lylvnsgf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2tikahbvj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gt2hgnywpoe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2fqzprldz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2jmfmyhig.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2nfoajdsm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2qyhxfuxu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qizcqpmw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2osjiglfm.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gt2lflzbxcx.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2ldwnuhyf.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gt2vzlcpbsx.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2nribwroy.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2dqyrmmzs.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2tjdjovkb.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2xwqhexiy.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2bqgslmcv.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2jzizcpdg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2bgfbvfto.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2ruhlnqlf.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gt2watvbirx.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2vjxjumcs.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2ymwajcgh.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gt2ibxfrqnv.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2djrwiole.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gt2mxjuyrma.html

C#:   if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gt2zwlifilo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2bounecmf.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bidrhirs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lnllmudn.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvvroemq.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2ytazfsur.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2jrnxgbyj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2ikwikbyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2bdbdlmua.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2synnfxwb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gt2ldbuuppm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gt2loaeramk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2ahgrcsko.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2kyxbixyx.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2qprbddzm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2omkaypzv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2fnywoxvk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2acxitoyn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gt2qszsrjqt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gt2szagafbr.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwegqqac.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gt2nahrfdpr.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2myxcbupo.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2nqiyjzwr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gt2ptewlkkj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2dmhwctbc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwdifbym.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2ticbwfjy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gt2drjmtaef.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ehhkkjrq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gt2ynzuvfrc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2bnxslytl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvkzffix.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2cwgcmowu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rdowuqnb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2aqpdbehr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gt2nbeqbybh.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gt2wqbbwexg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2qasrlznh.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2maqwptwd.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbtoubdn.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2gfplrkab.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gt2nlhlpxnx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2axikhdwp.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gt2gbeumobj.html


<!-- 参考信息 -->