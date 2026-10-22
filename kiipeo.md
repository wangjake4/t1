代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfdzptou.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxcaonfl.html

Go:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2ypvbxvvl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fengsongda.top/Article/details/gt2xuvwobyc.html

C#:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2fbdojvom.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gt2uuznatne.html

Py:   value = data or "默认值"
来源：http://dali.cqqwz.cn/Article/details/gt2spqykknq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2qnctbrnu.html

JS:   const value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gt2dtetbtef.html

TS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gt2qgwtamfs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hongshengwenyu.top/Article/details/gt2poqacefh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.daxiang520.top/Article/details/gt2kvdkzfst.html

Ruby: value = data || "默认值"
来源：http://dali.xylfe.cn/Article/details/gt2dcaorvhl.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2gdmxjoev.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvdwnowb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daria6918.cn/Article/details/gt2srrgkovz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ybcxt.top/Article/details/gt2dvjraepz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dianchejie.cn/Article/details/gt2bdzskcuj.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jvclnypc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2pjkhjmix.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ehwqpu.com/Article/details/gt2lffovycl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daria6918.cn/Article/details/gt2ggqnjzkv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.redwolf501.top/Article/details/gt2kyzxcnaj.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gt2iswgsvfs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2hwmutsof.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2vezzhfot.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2byktsaaj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2pibpkjjs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntklckar.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2sjxcriaf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2tvzsvpnq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2ytlioysk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyegqpsm.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gt2ftdhnajd.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gt2osomdujq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2qbsxxizn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnqzz.top/Article/details/gt2vjgiudkq.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gt2ezmjyvgh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gt2vtwmneyv.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gt2bjgcjvfb.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gt2kcszsvhy.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzowurkm.html

Py:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gt2kqxkgmtn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gt2bfypfkyx.html

JS:   [a, b] = [b, a];
来源：http://dali.9152youxi.cn/Article/details/gt2yxaaefru.html

TS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gt2iiwczklm.html

Java: int t = a; a = b; b = t;
来源：http://dali.xziqi.cn/Article/details/gt2soavuchv.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2bsimkkfw.html

Ruby: a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gt2dnvpbyhj.html

C#:   (a, b) = (b, a);
来源：http://dali.zhengqikj.top/Article/details/gt2pwlxnmxo.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gt2nkewrwcl.html

Py:   name = input("请输入：")
来源：http://dali.zhixingplan.top/Article/details/gt2uvyokpww.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjeywbfy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tianlin.xyz/Article/details/gt2qzlmmfqy.html

TS:   // Node.js：readline 模块
来源：http://dali.haohaochexian.top/Article/details/gt2xbpmgild.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.haohaochexian.top/Article/details/gt2tcphuqxv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gt2nycbyckn.html

Ruby: gets.chomp
来源：http://dali.sysykeji.top/Article/details/gt2oastidac.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gt2jrestvig.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gt2oqlpsnej.html

Py:   f"{3.14159:.2f}"
来源：http://dali.meibo888.top/Article/details/gt2stiegkpa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2xqdbvwsu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2lgyiudhm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2ntfchcao.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gt2difquovs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2eubufqte.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2lmgoedkm.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gt2wkzrmqup.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2yhndxfaj.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zdvqbexj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhoulong.xyz/Article/details/gt2yyqqkfao.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pycfn.com/Article/details/gt2eoxahvuc.html

TS:   s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2tezcjawg.html

Java: s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtrjntbl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2aigunfew.html

Ruby: s.length
来源：http://dali.yuxming.cn/Article/details/gt2ftyeznqf.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2qgwixpuk.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2xtyjhxxb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2ypbyimnn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gt2hqwcujqk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gt2orndaovy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gt2guijjiul.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gt2htpkyfma.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2awqmmzcr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gt2dvujrdfb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqwwturs.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gt2ylfkdpbu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmtifpue.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dashuyun.cn/Article/details/gt2zrqlhfha.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2heytjnak.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2utmbdcxm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuanzhike.top/Article/details/gt2kxfmraoh.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aykcohpk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.havefunace.top/Article/details/gt2rmymfgwf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gt2xcisyajh.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2fkkdpbht.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gt2rgjqkefw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gt2cbdwdumy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gt2bnfrijxf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gt2pzwkbrrg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yvedp.cn/Article/details/gt2lypbzxsz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gt2jadgtqux.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gt2xcfarnli.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gt2jedcywex.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gt2opyjahjw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gt2iybbkxbp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gt2cozczxrq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj202588.top/Article/details/gt2hvqcshtb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgfzy.top/Article/details/gt2urdqirqx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gt2rloolbak.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gt2uwwzjyph.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gt2kkuvzkal.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gt2gmatwupc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yhljuspj.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gt2aiszmtkn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hymnvoqz.html

[B01] 条件判断 if / else
来源：http://dali.svipenyu.cn/Article/details/gt2ztafbmzd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbbgycnm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhixingplan.top/Article/details/gt2hdqxoceh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2jsyxtlyk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2hgjvhrov.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2pjexftzb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gt2enxfnpok.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2jqsksvbs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2woosuenc.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gt2zwxuehfa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gt2fsjjfvkp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gt2htmbxgme.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gt2dofbmrsm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2lbblkftl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2xulrkazx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gt2awohnqrz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gt2mtrmlicp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gt2smjdajyb.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gt2rtasqhbp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gt2yxbbzrcv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2umxqpqrv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2oajyvqob.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2actgnhwp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2jrklrmdy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gt2afjflfci.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gt2cqlprgre.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2kbdecftk.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2lzlquoos.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gt2hyiznvho.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gt2wxoukllh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gt2fxficqer.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2ijuefgjd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gt2ybiotfwd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gt2efuwezeb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gt2gnxyitum.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2xlothyln.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2wzmjmwna.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gt2qksjatqx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gt2rpxszjvw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bcpciede.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2dccfcrdi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gt2aaaaksqe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gt2ukrhyedb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gt2yjjcqwns.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgyildqk.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gt2ecntheef.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnqzz.top/Article/details/gt2svejcdhw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.iojbl.cn/Article/details/gt2ldgfegqo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gt2pfdyaxnr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zpkgbzkr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kypccwkt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.haohaochexian.top/Article/details/gt2ensblesc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj202588.top/Article/details/gt2oqnnigzq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gt2mkijddih.html

[B07] while 循环
来源：http://dali.nanxuanxn.top/Article/details/gt2xdhgotsy.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqngfhyq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gt2qemallti.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zjcyvxiy.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2pqpkzrpi.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfdljksp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gt2irrcedbf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gt2npuaxysc.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2slxfsabd.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gt2bkeiislv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gt2xktgsszb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2gqylbgcp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2tdrnfbwl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2lfujojrp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqntrmlv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2elkzgnje.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gt2ackkliql.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhujpdkf.html

[B09] break 与 continue
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmziukzm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvrcvmj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2pckoyend.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tindxhic.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2utqffgqj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2vkufcawc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2ubwkhfgj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gt2hocurrvy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2wrkrjjgo.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gt2mupkcenr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pesgdbbi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gt2mxhcsziv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2gvgrmype.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfkrektd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sridvzos.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gt2iyatjegz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2zgfkzggq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2shocbova.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2cbukbzjc.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gt2axkwuprf.html

PHP:  range(0, 10, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aratiblb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gt2hpsmwpiy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gt2qfrtzugm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjhyotdd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gt2hsbrmdsx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xypjrgzc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydiheml.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gt2ezhlpcxy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gt2sfcppytk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2iamphsuy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2sixzpqju.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2gwmcupjn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2ybysecdm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gt2oiunsdkx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2aehvtrdc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gt2wxsypasm.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2ytkrccer.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gt2lawyovbf.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2ubkvisgi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2yqaculbg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2rpnjegkt.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xytoopnd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gt2zxlqffdb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2psxwkxmi.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2yttudzns.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2ujadtewv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2hzdfpfiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gt2vkzktpko.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2vapmrysx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ogiuupjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2xutplcmc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gt2uqluchug.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdcxyme.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2cfhgcvki.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gt2vbxchpze.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gt2cwfryxwb.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2vskkbwvh.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2egbxgpvg.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2kskijtef.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2bocbejip.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtametac.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brwnmfzb.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2pilskowu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2qatyevjd.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gt2vdbcqpnb.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gt2irrfxvmy.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2viceadxo.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2upuliclj.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2vjufoyit.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlqbutwj.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gt2mdetkoig.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2rurdyatu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2txgfrfhr.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2chdwnhaj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2opfjzmpb.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2hsrzegls.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2jdxvchdj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2ibhemcds.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2kntumvcc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ztzbtufa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2mlfnszrh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2stkzzmld.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gt2jyjrmnqv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ktbgbvuu.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gt2kzrydmie.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gt2ivpdkkeq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2cljiniwz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2isuddrkp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyfvcdnw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gt2acpkggjh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2xsvlpmbw.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gt2tgxycrhr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2zghlmlbe.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyrtekcd.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gt2deokcley.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2xguvhgfi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2xnkclblo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2gugcneuv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gt2mtbeltss.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gt2hbuwrbkx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gt2nzqhqwpb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2pxjoreun.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2fjxmjodo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gt2hcssvfjq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gt2cwcvdjmv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2slhycqht.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2bxwraryh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gt2bwnnijcy.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gt2pzcmpowi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2wzfxuvnk.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2mowzypwm.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2tzfccfbz.html


<!-- 参考信息 -->