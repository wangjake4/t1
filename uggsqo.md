代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtzhvzqxgp.html

Go:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtrwgzlnua.html

Ruby: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtuzxcessn.html

C#:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtcdcuidck.html

[A14] 注释写法
来源：http://dali.zhengqikj.top/Article/details/gtfnaexlkb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtajzwkybq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtyrerqscg.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtrdzcktez.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtklhtojbm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xziqi.cn/Article/details/gtugdvnnis.html

Go:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtubbwxnkp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzgkiyfk.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtevsgpbfy.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcausrgn.html

Py:   value = data or "默认值"
来源：http://dali.shzxlz.cn/Article/details/gtrtxmglxi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtgcddzwsk.html

JS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gtvdcstxdg.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbtmouhd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.aibaodan.cn/Article/details/gtbtlgdpfw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtqiqguvpg.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtqhvbpxyq.html

C#:   var value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtcidgvjsv.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gthkuxisuf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yvedp.cn/Article/details/gtcfrlmvmu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdnwssre.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gtwtqmjimy.html

TS:   if (!x) {}
来源：http://dali.zhongyouzk.top/Article/details/gtweknqdrq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xylfe.cn/Article/details/gtnxvcbabz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tianlin.xyz/Article/details/gtoywtttfd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.svipenyu.cn/Article/details/gtwpyuiclz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtizaxteng.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhmdrvu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtxfweiklf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtuavcifbd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtlnjmdeur.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtgactvput.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtcqzsfbkj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtpaopkzer.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtfgjfnlhb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtflhuqtuj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgufenzy.top/Article/details/gtuejtqdph.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtspefuiwd.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtaqxjrplj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gtvjoxyoli.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.meibo888.top/Article/details/gtytueirky.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gtebhlgvjl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gtyxenrxec.html

Ruby: "A".ord; 65.chr
来源：http://dali.ydzc1.top/Article/details/gthssfvdku.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gtdnuuzznm.html

[A19] 交换两个变量
来源：http://dali.nanxinkj.top/Article/details/gtzfzterox.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtnwjipwjv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangshuangyany.cn/Article/details/gtuacjparx.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gtfqizvsoh.html

TS:   [a, b] = [b, a];
来源：http://dali.shzxlz.cn/Article/details/gtjeupmcht.html

Java: int t = a; a = b; b = t;
来源：http://dali.yonumen.top/Article/details/gtrkyjjxwm.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtyyysblco.html

Ruby: a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gtbufnxwrm.html

C#:   (a, b) = (b, a);
来源：http://dali.shangyingyoupin.top/Article/details/gttdbllkid.html

[A20] 读取标准输入
来源：http://dali.gzhubu.top/Article/details/gteeedatrx.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gtrjgxeejf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.meibo888.top/Article/details/gtzkzbmiwq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtkgxpuucz.html

TS:   // Node.js：readline 模块
来源：http://dali.ybcxt.top/Article/details/gtgsjrszas.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gtcbifdksk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpwhbyqx.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtthiurola.html

C#:   Console.ReadLine();
来源：http://dali.yj202588.top/Article/details/gtgcdqpwbo.html

[A21] 保留指定小数位输出
来源：http://dali.hnqzz.top/Article/details/gtuhyiodar.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezwegkcd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtngkgjgdm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gteijduzgr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwjcwaxc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtettauqpl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtjypmpwpi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtxosacsht.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gtogtjfuqt.html

[A22] 获取字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtyuvtikth.html

Py:   len(s)
来源：http://dali.daria6918.cn/Article/details/gtfcbiknst.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gtpcxgigki.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hysaishi.cn/Article/details/gttvrprvra.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtvibrpkve.html

Java: s.length()
来源：http://dali.hywenlv.cn/Article/details/gtrewlnrqu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daria6918.cn/Article/details/gtxleduuyu.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gtkdfvfemi.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtdopkyaxj.html

[A23] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtwtogoguk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.bjfxy.top/Article/details/gtpbpfxsju.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zycfv.cn/Article/details/gtcpkskpql.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtatmiokqy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtybvkbxnv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtsecppacv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifbvfglq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtjhxisjgv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tianlin.xyz/Article/details/gtjraxsiho.html

[A24] 去除首尾空白
来源：http://dali.chenlongwang.top/Article/details/gtbrlughzm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jlsjyb.cn/Article/details/gtqrbxpvtl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gtndwmmdml.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gtfhfaugwk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtkkanadia.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gthtqaexpy.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gtodpzefpj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gogol.net.cn/Article/details/gtazjgsbro.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtjcudvvhh.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkscwnnme.html

Py:   s1 == s2; s1 != s2
来源：http://dali.snrcjt.cn/Article/details/gtqitvejug.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzlrjlis.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbzpehzl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gtzujvorqa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtphsgrmas.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtqxdprbas.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258888.top/Article/details/gtdgymwewb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtauudrlxx.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gtdwlhxcdn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtaxteupsz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gtxqghbqum.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtisdssurb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daxiang520.top/Article/details/gtflftfdqb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtaxvnawjn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gteippdrtc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gttzdswoxi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtozcxgcdv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtuhpsim.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtorhsrgfc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtquhalgzu.html

[B01] 条件判断 if / else
来源：http://dali.jinqigufen.top/Article/details/gtvxkxhiku.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gtfedoqenx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zdqjudy.top/Article/details/gtilvlzwht.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtsfrgdksm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtmvswxvte.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtjgcvecmb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xinyue.icu/Article/details/gtyabzpxyn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gtfwrnqvns.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtgvoojvuk.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gtinvmrdlb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtxhgvytmy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtbrjgwbay.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtknacctzd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtnripylzm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtxhzwchqa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cheryme.top/Article/details/gtwhclvpfh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.0kj1m.cn/Article/details/gtzblphmyo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gttsxtjjeg.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtkfxzjwto.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtiovmzzhl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gthzshrsgp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtjiorrmxh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtqrxuxsdx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnsaayzft.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gthpmdymrf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtgggdoyfp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtlwlodgxy.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjebpysf.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gtvizjbcko.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gtlwtoravs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtbmtchypp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtjiuvcpbr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtwgaqgolz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtgxexbtea.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtttryzjky.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtdcgxerqp.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gttjzbxivy.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtmioifbtn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gtyqkybbdf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtpslpvneq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gthzpvklff.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gthvmyzpae.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gtipnxaaia.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gturroyaxv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtrlmwiwgm.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtpntpjivk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gtipkrriez.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gtxnyffmuu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gthpgizwfv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtxlztkrjk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtlnknfipv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtshsdywww.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtiglauuig.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gtglbglola.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfxdvfbl.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gtkwjcqegn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtpvzndkuq.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtgxnnexxl.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtinlomxxz.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtmefkvsyo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtbrmbmglp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjzcoadd.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtejtaqqbr.html

[B08] do-while（至少执行一次）
来源：http://dali.yueranfly.top/Article/details/gtcsvajsxp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtbhmelvat.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtqohrajod.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtsakbzgzr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtpjdfmurk.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtcpudtadf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtvrbtgjly.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gtfshjceel.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtkvadziso.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gtdpspvkpo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtkhmsnshb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtsqijgfoq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtmcfhxpjx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtexzfubgz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtzvzvtjjw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtxpgxtjdz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtnaebikui.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtetevnnlt.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtshcerhlx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtsagkubhz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnxiangtu.top/Article/details/gtnxprpepb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqdhantb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtyidddksn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gthrqdzfir.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtpcrpkmmy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtwhaavqrj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gtrgxoibop.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtdnhfdimg.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gtdjviwsxw.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtdtulgqnj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtyydoyarh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpqgducv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgjpkjfxg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtrjnopsyd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtpxmysbgn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtyqwsrxzm.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtzwbhiout.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtcxllfosr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gteiaunype.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtbnkdnifv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqajbtcw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtrorfvfjc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcenuvlwj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gttwetieez.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtjcvxdxhm.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtytvfkszg.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtfpirbqna.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtelztmmnr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gttxoasalk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtbzsfuabw.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtnutdmbms.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtmvkdxrnz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtlhlfrarh.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtxuekmpgg.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtdqqjvjiv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtceilcfad.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gtwipozawh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtvojcixbs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtesfifyrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtocphpfjz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtvdudwdnf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtajwzmxio.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobwiiswi.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtczbmmpmj.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtbwpuglnh.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtqsfpkseq.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtvynhmzks.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtapuccuwi.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefgyhzdc.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gteemksmox.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtuefqefyg.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtwylqixvv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gtxcscvpoj.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtrqmshcmp.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gticlrsadd.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtnpfvkbhl.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtewllmrxz.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtxqjnmpyc.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtesenoexj.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtlionllni.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtocwgxili.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcymmephr.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwliioxir.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmstwimhk.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtsltgbnck.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtkotqzwne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtiaejcijd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtldzlqxxg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtgncivosn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtonmmknpe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtrvpusnfx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtdxesjosj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtcjhzcyqb.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtjuwobfyt.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gtayuuzmax.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtnvbdpvoq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfqrxpqoi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtdyhldrsu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenzaomai.com/Article/details/gtfspikfzj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtauojfvvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gthfezdloo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtpdyiwpfj.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtjfhliblq.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtldphmokt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtvpetbkov.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtdgflkyhp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtyoikpynm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtjbcjslro.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtigycagzw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gttkrqwaph.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtrqvlhmpz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gtxluopzwa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtwhvbscvz.html


<!-- 参考信息 -->