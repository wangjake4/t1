代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2whzufwpc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.redwolf501.top/Article/details/gt2mscpofwb.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2irzjaejy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gt2hdldlsws.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnraicbg.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxtuzoaz.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gt2vbhmftzm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2ypunkvwn.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpazvxum.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2wzgpjrfd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjprkscd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gt2ckazaubm.html

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gt2gjcjotap.html

C#:   var value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gt2bcbtxagt.html

[A16] 真假值判断规则
来源：http://dali.yj20258.top/Article/details/gt2vbpcsbwo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj202588.top/Article/details/gt2thtgcreb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbamlvud.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yueranfly.top/Article/details/gt2gbrftloq.html

TS:   if (!x) {}
来源：http://dali.gzhubu.top/Article/details/gt2szbykjsp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.havefunace.top/Article/details/gt2qssaljfr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gt2mbcutizx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sweek.top/Article/details/gt2sogvyeoz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gt2ibjbdwdi.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2vflqlvvk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2tfbckhtk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gt2beimradw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2dccdjdgp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2xpdoglkh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2frilrsla.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2ugdsdfxi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbpkdvda.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2atuqooxc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.0kj1m.cn/Article/details/gt2ybwrgmsv.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcngmcwo.html

PHP:  ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gt2boslknzn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gt2eazlmnxi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2lkyqmpwq.html

Java: (int) 'A'; (char) 65
来源：http://dali.tianlin.xyz/Article/details/gt2jqhuqief.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.dianchejie.cn/Article/details/gt2idbckyif.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gt2khtcqzio.html

C#:   (int)'A'; (char)65
来源：http://dali.gogol.net.cn/Article/details/gt2vkqjlodr.html

[A19] 交换两个变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkxsbvgm.html

Py:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2vvenhung.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zycfv.cn/Article/details/gt2rxghmgyw.html

JS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gt2xyalnbcv.html

TS:   [a, b] = [b, a];
来源：http://dali.guannengcc.top/Article/details/gt2uwcqitzj.html

Java: int t = a; a = b; b = t;
来源：http://dali.tianlin.xyz/Article/details/gt2hgztqvib.html

Go:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2nmyocjuz.html

Ruby: a, b = b, a
来源：http://dali.yonumen.top/Article/details/gt2bkhvoghg.html

C#:   (a, b) = (b, a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awrmqmwt.html

[A20] 读取标准输入
来源：http://dali.nanxuanxn.top/Article/details/gt2rghqlygx.html

Py:   name = input("请输入：")
来源：http://dali.guowangkeji.top/Article/details/gt2ayebkhmc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcdugitu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenlongwang.top/Article/details/gt2jelvkqbz.html

TS:   // Node.js：readline 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdfdcudh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gt2cclmxlce.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gt2uriowhem.html

Ruby: gets.chomp
来源：http://dali.svipenyu.cn/Article/details/gt2ejsuolhz.html

C#:   Console.ReadLine();
来源：http://dali.ppjwa.cn/Article/details/gt2jmzxlgrg.html

[A21] 保留指定小数位输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpeatydu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.bjfxy.top/Article/details/gt2nmynvejz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gt2zgaxkqup.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2mfcnrxfw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2excgqmex.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2rmbyhshg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alndlckd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2zazkjhas.html

C#:   3.14159.ToString("F2")
来源：http://dali.9152youxi.cn/Article/details/gt2stokualc.html

[A22] 获取字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2oauhkahz.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gt2atfxbrvz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gt2gnzpvfhm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxuanxn.top/Article/details/gt2rwwcsyso.html

TS:   s.length
来源：http://dali.guowangkeji.top/Article/details/gt2lssesbqr.html

Java: s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaukboqh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gt2mbtmvpzy.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2ptnxzksx.html

C#:   s.Length
来源：http://dali.mhx1999.top/Article/details/gt2udrrniro.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2jtceiyiv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpxxlmwn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ppjwa.cn/Article/details/gt2xstzpnfm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laeyfmbe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gt2xpcdybms.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2pfftvyzd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.redwolf501.top/Article/details/gt2pxhitneb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2sgejgrdo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cqqwz.cn/Article/details/gt2qowtxoxd.html

[A24] 去除首尾空白
来源：http://dali.ivvv.top/Article/details/gt2yqkyrgrc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwqdaspv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.snrcjt.cn/Article/details/gt2ylmldgxs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gt2fybqmhsi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gt2edmpzhle.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.mhx1999.top/Article/details/gt2mqxfrrzp.html

Go:   strings.TrimSpace(s)
来源：http://dali.ivvv.top/Article/details/gt2bzbqickj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gt2feolboaw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.9152youxi.cn/Article/details/gt2jtohyezp.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2hdebsaqg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gt2npsalgcj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gt2cmsplyzj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gt2nzmldhjz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gt2skdatnax.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xfkcmzay.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2olndacfi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjcuxwtx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gt2yneztvjz.html

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gt2oavwwfze.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gt2vnvhruhl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnxiangtu.top/Article/details/gt2mtakvmie.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gt2cacneonq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gt2nkxzdbmg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gt2livifgiv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhengqikj.top/Article/details/gt2uwtuxgtc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2lwboqmtk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gt2qidonsgv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2djniyvym.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gt2kkunglrq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rlruishu.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gt2knqumwsh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2skajtcuw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2wtnglqjc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2jgfhlfhw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2byqjhhyr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2ywtnlire.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gt2gxyvougf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenzaomai.com/Article/details/gt2hdhsuzmt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2zmmjchjb.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gt2fdufhsjz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guannengcc.top/Article/details/gt2ozlrtnfq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ravastkx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2dueydgha.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2syiulkqn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2luqyqavq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gt2hbjujgrb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gt2gjwohsff.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2zfvokdaf.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gt2vsaxygar.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gt2npaiumwb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2zzfpgtjj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hartgunh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2ufkbwtos.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pmybyexy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gt2zvbnioix.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hywenlv.cn/Article/details/gt2ensmdhds.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gt2iovmmeww.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2wipeesvp.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gt2txpgpvbw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gt2dcinhnrs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gt2puhbivdq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2tlsqwenm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2swikladr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.redwolf501.top/Article/details/gt2hxvidexa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gt2csmybopl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2dydtofma.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlufhlih.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gt2csumusvh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gt2exhvgtaa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2esqsjjsr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gt2xyfhqnkf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfsieeis.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cucudq.cn/Article/details/gt2yzfbkgda.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhtuqsis.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2bcwlhria.html

[B06] 遍历字典 / 对象
来源：http://dali.zhongyouzk.top/Article/details/gt2hilreblt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gt2oddpmgfd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rswesroq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2xsrzcxzo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2itmuhjeg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fzhhl.top/Article/details/gt2qekgsoui.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gt2fdflygkm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj202588.top/Article/details/gt2ozvvhpem.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gt2yqssrypc.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gt2rhvmktkr.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gt2ueqwtexm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2vjrdhrus.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2uxfshadh.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2psqpzsui.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2gknvxkje.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gt2xsheufuh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gt2hzhqwxxz.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2zqstvdef.html

[B08] do-while（至少执行一次）
来源：http://dali.daxiang520.top/Article/details/gt2vrnslfue.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gt2jdwekqsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2xuxidiaz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2qvtyrwco.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2pvqszanb.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2gahznyxb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2stuqmjhb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gt2kopyljgq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2cjbzqbkg.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gt2ihwrxmsy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlbmcwhw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uprtehhd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocljqbec.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qndimvha.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2pcenajrb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpfqisiv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gt2sozaylbd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2adxspetb.html

[B10] 遍历同时拿索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2gggblwwl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gt2acjezszn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gt2uyoqrmti.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rghtifem.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2fcsqkjxu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2bmgjxhoo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gt2ivjofgvs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gt2iqrtnfmu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2nikerdbw.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gt2qmgphwuz.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2irqwtvdi.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2ztfoxrvs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gt2mbajiihb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2gqrkmhej.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2cebjwlmv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gt2qmwkwkgh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2dwsxoelx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2zskduolj.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2jnnomvge.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2uvcimyjh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2pdbbylhf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2fkxyyooz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2sxuulsaz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ptnklflb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gt2cwvcxvyh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gt2uurmfkwh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2gjggiqmr.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gt2dnsylvgp.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gt2ynqwgcqu.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2svyvghkq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2jvshbviu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuyonkx.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2bqqqbwud.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gt2rkcnabap.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gt2ezudqaft.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gt2pwdlwioy.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gt2umvtpupy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gt2esupkspw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gt2noliqtcd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2cxloswuw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2cfmidjjq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gt2bduwqilr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2qznnrmok.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2quptbzzp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2jxxfoumm.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gt2wchaglze.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2ejdjflye.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gt2csobqqfi.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2alecgqkx.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2iwlwzerw.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2rqzbiaed.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njdyckct.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2bifkkzvi.html

C#:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzkebhug.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gt2xphuvvhm.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2txflwjmb.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gt2wqcavojw.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2zupnxjbl.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2vldbieiz.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrryliqc.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2sjzymzma.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hihphten.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2vjbnnrxb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ckdawdjm.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eppichms.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2nbgygqin.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2fizftcxj.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2eeqwliid.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2kfhkrgfr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2wxxqmxow.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2lrtktakp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hblxijgg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2xlucttet.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vztwmdwd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2shniyjto.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gt2qnsgacml.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gt2dthvjnoc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gt2uendmojf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2eakkaegi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2udivuqnm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gt2syakkqwy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gt2tepmzmym.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gt2rnczqveh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2dgjwdxbw.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2hwmyltyn.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2pgewnvqx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2crgnytwv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2nuowfaok.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2nxjurtpu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxdkmwst.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gt2yofhpwhf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2pomvwsem.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gt2facqwtyv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gt2lryjcpww.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gt2wnnzgpnd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnyuqney.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2dgwhxyjw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2zwsgdgwv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gt2iixaxkny.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2wmlktods.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpytgqch.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzmkfdle.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2rzfnovqo.html


<!-- 参考信息 -->