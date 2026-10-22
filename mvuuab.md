代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtoagdvpyq.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gtkktcstbd.html

Py:   value = data or "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gtkkimtlxj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtpxgnjiud.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtsagvimaa.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gtjxuuehkg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gtoxilcrvr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jianghu66.top/Article/details/gtneswdtxy.html

Ruby: value = data || "默认值"
来源：http://dali.sxryk.cn/Article/details/gtqimhmpgs.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtceaaefue.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gtxotjydmk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gtafbeaenv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtwmtgysyl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtvpfiaalg.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gtnlhlnxni.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gtbbdfyduh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmatrotex.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gtcqftiivp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtklcdiwwr.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gtgyozlsjt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtafxxzpue.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yongpay.top/Article/details/gtnzjoqmaf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtuxumaqct.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtcbrcalbc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtyjpyllkr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtrjjzibmk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtcwlbntru.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuchnevt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xinyue.icu/Article/details/gtozfejjif.html

Py:   ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gtikqibcnp.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtjdzwmvlu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtetlofrkg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtnvptwuen.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtxbwnhkvz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.316326.xyz/Article/details/gtswcxmfnm.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgfzy.top/Article/details/gtcsqaukee.html

C#:   (int)'A'; (char)65
来源：http://dali.yuxming.cn/Article/details/gtdxfmmnxe.html

[A19] 交换两个变量
来源：http://dali.yuanzhike.top/Article/details/gtfymzzqub.html

Py:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtvdcsvjhq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.316326.xyz/Article/details/gtvbguolky.html

JS:   [a, b] = [b, a];
来源：http://dali.birdmap.top/Article/details/gtvatnxcau.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtxwnkuwic.html

Java: int t = a; a = b; b = t;
来源：http://dali.sxryk.cn/Article/details/gtjaaietgn.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtofzaevfq.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gttacbhbpy.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gthcsnhrwb.html

[A20] 读取标准输入
来源：http://dali.jqgfzy.top/Article/details/gtalnzksqq.html

Py:   name = input("请输入：")
来源：http://dali.pengpengdd.cyou/Article/details/gtbhdmfhuo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtmpqhpiga.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtzuokxorr.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gtbcuepfkn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj202588.top/Article/details/gtijjsussj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jlsjyb.cn/Article/details/gtrmucoeah.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkeblkhl.html

C#:   Console.ReadLine();
来源：http://dali.daxiang520.top/Article/details/gtrpnftywe.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gtpxmwtnsi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuetiantiany.cn/Article/details/gtycplxuug.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gtgjiianml.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtizhqchxu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtcwwfkudu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtcjuypgmm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtquhatdhx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtnfvoiley.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj202588.top/Article/details/gtzthfdvhc.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtyiwvdrii.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gtoqbgoykv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.redwolf501.top/Article/details/gtldlbypdc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangshuangyany.cn/Article/details/gtqysaghpm.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gtqbinsjkr.html

Java: s.length()
来源：http://dali.fzhhl.top/Article/details/gtmlrukrfu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pycfn.com/Article/details/gtomydawtd.html

Ruby: s.length
来源：http://dali.ehwqpu.com/Article/details/gthoswqyfi.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gthkjjzwus.html

[A23] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriveqcrq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.c1oappe.top/Article/details/gtuufqkrtc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hysaishi.cn/Article/details/gtsykprkqs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtebeevfvj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteapokhbn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gthyyduihx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalqllkjq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtohvsoeqi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gotoacloud.top/Article/details/gtbhgjiobl.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gtbcavxyff.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtgvywjubk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjtedzdla.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gtretdqckw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtoboefnky.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.redwolf501.top/Article/details/gtloqvbhzx.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gtsyvlrmtv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtanzgbntp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtcpfwcklt.html

[A25] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtcnaaccnr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gtnsqfoout.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gtikhpcyyj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtdpdaywiq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtumxlokgv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gtauppvxki.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtogehotdw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xylfe.cn/Article/details/gtnoktqymp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfzzxrlz.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtmiqgxjdc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gtiherlhea.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gtmklutmfh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gtbxjgbilg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gthctjgvvx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtjaobrbrl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopzhusyq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gtuijkized.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtvscdfxsh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwjwzcmhc.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gtkeoayxqd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmthrnhnd.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtasazkxdb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtzoulmgbr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtiovdsazm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtrdoswepf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtyrzzcrrt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtnzvlkfgp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.iojbl.cn/Article/details/gtbfaedsam.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtvvmlynug.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtcpsajxvr.html

[B02] 多分支 else if / elif
来源：http://dali.zhiwuduotai.top/Article/details/gtpgvvmquy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtbrscenlo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtwiteamaj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtywbrcwih.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtsbvozdxi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtvccwptps.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gttyvcorjz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtvnzvzbce.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtjnjhrkpk.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtqhkxvrin.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gzhubu.top/Article/details/gtfsndpfch.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtpsfnkccv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtzdqgiful.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gthimewrbh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdatnqgfq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gtihhjlysr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xinyue.icu/Article/details/gtklxwkahc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtdbysqhap.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gttrygoldq.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtsvbzlzrr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtslbnavfp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtdppbgsug.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuatwfptt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258.top/Article/details/gthbuuentt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtwdyaarnf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yueranfly.top/Article/details/gtvldzlrtc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtgbcvvoey.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtbygnesrm.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gtymnnfeyz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gtpdfnwwvs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtjbyngejl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtuxcvyrkd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuanzhike.top/Article/details/gtgcaxjuun.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjinxowt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aizwys.cn/Article/details/gtnuqxsvtz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtthubcdou.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gtkckhofsx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aizwys.cn/Article/details/gtdxdlhhbb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigufen.top/Article/details/gttqzsqela.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtwdeqwvlw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtptpkidrc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gtfwhxjkds.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtlgvvisgv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gtyooothiy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtkfpydarb.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtvpgmejlh.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtgxilrtuv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtlxdhtblp.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyyhijkwi.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtxyxodtsg.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvrgcild.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gtmhfyqkpn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtecobfjwg.html

C#:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtohtfecvf.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gthcbvikza.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gtgbndtruc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtdjxiguot.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtwmvxvgen.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtbsjuseqy.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacoqhbur.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtjzhqdprg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtkuzhgbei.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gttknskqhf.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gtqcrfbdbq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtjxupivdq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtzbkkxwfq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtomdcgczc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtiidjvrrb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtsplepbpb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtywnowfet.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtehzpxgvs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtqpjfnlha.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gtroiognkz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtdzwyylhs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtufquosvf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtvcnrdgkt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtzcjealjq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtabwmxodj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtjipfiklx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtbankjitq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtwjzpvvqa.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtkxoctxay.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtyokclypg.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtclptwqit.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtzqyktomn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrbdzcqkv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtghufwlmi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gtpkstidgx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtnuhbqhqu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtepymsyfk.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtumpvmioj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gtgnfriocx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtmuhlaatn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtquhokkvl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtibeqedlw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtbbtkrivj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtlstriobu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gtzkdkewlz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtnbofttbe.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtnzavawln.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gtsulypery.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtmzbgisgc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtuhpaszfu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtmzqwrtwe.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtqmrmjied.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtwriluccc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtjnyrozcl.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtcneixyvq.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtpcybhaqv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gtclfhcqnj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtsvialnhz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtdtnrdelt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtuxszxmdq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtmybwqlpx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtnehveakr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtviicmoic.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtkgpjudvg.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtrcccszlr.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdhmesww.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbyfmvjw.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtgoutycjq.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtwzrhtnjl.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gthzlhbjgs.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtfmbbufuo.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtfiarjzdv.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gthtzmvvvi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.iojbl.cn/Article/details/gtaqxgghqv.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gtnbwelnrs.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtcdvbpmxp.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtvvdzntvu.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtnahfhlyn.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtvqmkrawi.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvalannzf.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtpvutscfc.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gttkcxkgjx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpssutbce.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtgsvacbkm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiozqlhfu.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtmocesklv.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtplygtvuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtjkgwijmh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtuttviikk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtzhvuqfmd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtxhpodgag.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gttelqhxmo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtikngzqbu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtsrtvvodl.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtzjhkgphc.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtbpxoydas.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgtcikxui.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gthgyvvmne.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxsbtbnnl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzlmkva.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtlowumxia.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtmhwapcft.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtogdgorir.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gtoiqdjdqn.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgcpoleu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtshytaogx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtmbozbejh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfccfdzxt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtiylkdhur.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtyhlsjbme.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gtewmgyvuy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtrtcpykaa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpexzahu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtxycqwoes.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtqxelystx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gthzfusmvn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtwnshhizj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtlrhotfaq.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtdlpehumy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gttnrxlpii.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtlmauwcal.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtnsbzezbf.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gthnnayctq.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtnrfawisl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtxunqaeas.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtrujnjpaf.html


<!-- 参考信息 -->