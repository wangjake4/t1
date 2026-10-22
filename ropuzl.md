代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gt2pofrgvty.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2iysqyird.html

[A16] 真假值判断规则
来源：http://dali.meibo888.top/Article/details/gt2npbgidll.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2hczxixgz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tanke756.top/Article/details/gt2ayzznbom.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gt2mxuddckf.html

TS:   if (!x) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkypwmqd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2bkktyyaq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2grmrevpb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.9152youxi.cn/Article/details/gt2ddinhvyp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2ygssklvi.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gt2troeujog.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2rodmecvi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2zfsmrchx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2zusozgcl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2enwzsxfa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2nqzqkzik.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2nklhptrh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2atxvsxtu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2botowwod.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gt2pumhkgwr.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gt2vncdoeop.html

PHP:  ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gt2tnswvten.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gt2ascpgksx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gt2fijyuenq.html

Java: (int) 'A'; (char) 65
来源：http://dali.jyoumei.cn/Article/details/gt2uzumzrmr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkmttfwc.html

Ruby: "A".ord; 65.chr
来源：http://dali.guowangkeji.top/Article/details/gt2kstsvqtg.html

C#:   (int)'A'; (char)65
来源：http://dali.316326.xyz/Article/details/gt2smxwdups.html

[A19] 交换两个变量
来源：http://dali.gogol.net.cn/Article/details/gt2qfvpjpws.html

Py:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjfqcnhi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gt2sznyuxcv.html

JS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gt2mewxljyv.html

TS:   [a, b] = [b, a];
来源：http://dali.cheryme.top/Article/details/gt2vvsghpxz.html

Java: int t = a; a = b; b = t;
来源：http://dali.gaohongyu789.top/Article/details/gt2czetgjvb.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gt2awmmzfze.html

Ruby: a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gt2nhwwzsqe.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gt2dyirglbp.html

[A20] 读取标准输入
来源：http://dali.bjfxy.top/Article/details/gt2zojwpqqy.html

Py:   name = input("请输入：")
来源：http://dali.nanxuanxn.top/Article/details/gt2ixlturfz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxxzdody.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gt2ryouuyhl.html

TS:   // Node.js：readline 模块
来源：http://dali.hywenlv.cn/Article/details/gt2tzqdvlca.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aibaodan.cn/Article/details/gt2poljvecq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzfnwohq.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gt2smgarily.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gt2dupznvno.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gt2bmryuxha.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzmtogok.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2gyrneren.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2scszqerb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2pbidsxdh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2oeihdqjm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2qznjkidm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gt2dknlcnoc.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gt2tpeapfxt.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2vsoeeenw.html

Py:   len(s)
来源：http://dali.316326.xyz/Article/details/gt2qdokiluo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2xjxmrtos.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gt2vzozhkrd.html

TS:   s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ychpzbwj.html

Java: s.length()
来源：http://dali.xylfe.cn/Article/details/gt2puqbnhdf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.iojbl.cn/Article/details/gt2seurvvnh.html

Ruby: s.length
来源：http://dali.zdqjudy.top/Article/details/gt2skyurcuw.html

C#:   s.Length
来源：http://dali.yvedp.cn/Article/details/gt2sbvfqmyc.html

[A23] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2vexdtbtz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.redwolf501.top/Article/details/gt2qmemzeyc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gt2fpcxuuvx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gt2fasdoavh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2icnzjkqk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsqmsnrj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sweek.top/Article/details/gt2nxmsujwr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2gtyppeea.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuanzx.com/Article/details/gt2topzeeqs.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihwsuknq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gt2vyhrlonb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.andypj.xyz/Article/details/gt2dfjmhbeo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2jndvuajq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2fedtrzsh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2bmjtlcpl.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gt2eqoldnlr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gt2xaakbkgv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2ztjkzamy.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqwphjto.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gt2eglmihvm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gt2pvplfnai.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gt2npbuzkso.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2tuhegwii.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gt2eufjzmvl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2khdgeuzx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxneeytl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2nwmaakbm.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gt2pfgflphn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyyzkpuy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gt2gvanqoak.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbmcrenk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gt2qbkzpckd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzeulqvs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gt2ygxnoqkw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gt2psdwwizl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2mrlubjno.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2nlepsiye.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gt2wfmurkui.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ijzujsll.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gt2stwywdxd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gt2apsvirgs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gt2prodkgmc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2rrtxrujy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2wsbnnjmc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2xpybpnvy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gt2dvufupdb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gt2jhcjilor.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2sldmjvky.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gt2zrwvknos.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gt2yqezbdom.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pkyxmmvm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gt2sdyqffor.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2mnlpamze.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpdyqxpw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gt2ekstmwhq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gt2gyhnhhsz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eudsxkkh.html

[B03] switch / match / case
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwbrgbcf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2osohqzbi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gt2dyribndn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2risnwmsp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2lyizogsd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2nddlnmwj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2dskjsuoc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gt2ctaiqcys.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gt2rfqoiulv.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gt2tuelvihg.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gt2iyohijas.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gt2mczvlryt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2oevigudv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmxxrwj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gt2frejyqvh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gt2mdadhhyq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gt2ilnzbzsk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gt2gidjfpzh.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2sncwmael.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gt2yebltlft.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zqzooeuk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2tabgekdd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjqhuwzo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gt2evnbafhd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gt2otxnlgtq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gt2vxlvnwjq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gt2jmtqaanu.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gt2golpzgmo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gt2espafnmv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wkyatsgk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwwfgfo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuivzifz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gt2wkymupat.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gt2hspyeibj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gt2kibvdqxf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gt2awtyldcx.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtfepulw.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gt2bifcpche.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mdgbgsgw.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2qibzqtgy.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2sewnmitj.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2dlobzjcz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkwbarrz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gt2xxndrfwu.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwtfhcuq.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gt2holdevaw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gt2nnlskxvg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2vitmdwjz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2npxkoxye.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2veutrpfp.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2dcgqxlpz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gt2qqmrhkvv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxcxptse.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwjceamo.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gt2qyorxxpg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2onrutgxr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2vadjaxek.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2silnlsac.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2macujfst.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2vnkhsdfl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ockbtouo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fndhvxfy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2egtghkwo.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gt2picizdqr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gt2zhcyldav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gt2wixgqagh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gt2nyvbqyoo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gt2ocgjrlsv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gt2gcccmzpg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdtfnflr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mypwpshz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdsqvbts.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2ggoyafmu.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gt2briogpdo.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gt2ldopzkat.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2wbnmyzcj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gt2mtnzuohe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gt2eeazpkzd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gt2iueadcsw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gt2vivrnqod.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2khrhvkpa.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2aqynxyjz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gt2abrswkeq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2cxcwidui.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gt2kvhhevco.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2rlkfoadg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2fyzlmvgd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2elkurlwp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gt2etztxrmx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gt2raunumve.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gt2nalsjhgx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2ohgbccic.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gt2earbeqzm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2kxtvirws.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2izyduyzt.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2zsqgannt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gt2ttsegqme.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gt2lfbkqbrc.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gt2qtzsrxgo.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2izswoehn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvefomst.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2euubxwxu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2kyvtqxwy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2cfbklawl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2kgsrudpk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqctytaq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2cubiltxz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jsiorpkg.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gt2oorhwvwu.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gt2imezxldn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcbnuci.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2sdipncfx.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2gbtdknsr.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2hlhaagmc.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2rbxekigd.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2tymercex.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2awddapxu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bugiolyp.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gt2apoenxsf.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gt2kkusapsb.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwliwapc.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2ezwbfnxp.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2pfzkcsac.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gt2exioodkv.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gt2szhmgmhq.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gt2jcqmwwfp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2cxkghfra.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gt2aqnfeyck.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2coujagiu.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ljekesta.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2xlqmctgj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2onvwfege.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2sayqdvxp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pddklaks.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2zduvyani.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyuuxhwu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gt2gfdtnkqw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2kkxoywfm.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gt2dspdhjbh.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2lxtggdyv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gt2bcwlxdxg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2qqlbykjh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2spfxbtpn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gt2psiwvvpd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gt2gbsocjwo.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gt2qbjcnxcu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gt2ulkbdtpx.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gt2lsvqnsqq.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2lzgrvnih.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2svkidhee.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gt2leakqfyi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2ydcjufok.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gt2lipyuafi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2wmegudhv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2odovnekx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2wakbmupm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gt2rbtwqbmh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gt2fbhtzkup.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gleldeau.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwchnavs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2xehuiyhp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2xvkkiwxu.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gt2onfolvfg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2gfbmvqia.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2foueyrca.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gt2nozxbrvv.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2quxawuuk.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2gyifcvnf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2fdwaixmj.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2fautkxya.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogzdutpf.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2zhfdpkcb.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gt2lamajqzn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2bpwnddcp.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gt2smrdjjjh.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2mzwrkuds.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttfylbps.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2xezxdqbh.html


<!-- 参考信息 -->