代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.yangfankeji.com/Article/details/gt2juggviab.html

C#:   var value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2ghwuvqcs.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibfsrlgu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gt2lczgrfan.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dashuyun.cn/Article/details/gt2nwiqgdql.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gt2kfoiwsmi.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pexncmyf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2igyqszvf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gt2sebqthbk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.aibaodan.cn/Article/details/gt2hrbbyzku.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2qbksnmgc.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2litouscy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2pcrzcrtn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2krbexvfr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gt2wplxetlv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2egxgezju.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2svpydzba.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2ylufrtyz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2pwoszxqp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2iwkmsrng.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2elhprgve.html

Py:   ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gt2sqqefvfc.html

PHP:  ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wicacmcd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gt2wfahuaxo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2fovegtks.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gt2yyjgrapl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guowangkeji.top/Article/details/gt2ydwejwmc.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gt2ydbltobx.html

C#:   (int)'A'; (char)65
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqnoqggj.html

[A19] 交换两个变量
来源：http://dali.shzxlz.cn/Article/details/gt2howetanf.html

Py:   a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlvrfuvt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvtjfxcw.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gt2jnbpevlx.html

TS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gt2imgneodw.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gt2ikvuaica.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2iedkaiir.html

Ruby: a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2vpsgrzpa.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2jfisiqoc.html

[A20] 读取标准输入
来源：http://dali.aibaodan.cn/Article/details/gt2ecvuyusp.html

Py:   name = input("请输入：")
来源：http://dali.jianghu66.top/Article/details/gt2perpicuj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigfzy.top/Article/details/gt2fammbffd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sweek.top/Article/details/gt2vogjtemy.html

TS:   // Node.js：readline 模块
来源：http://dali.ydzc1.top/Article/details/gt2mvadzotw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aibaodan.cn/Article/details/gt2tdcmdqkh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gt2jciqiskg.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gt2uctbtbsz.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gt2zyjeigfq.html

[A21] 保留指定小数位输出
来源：http://dali.yanxiufei.cn/Article/details/gt2wanmvyxm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gt2xikfttou.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmhgancp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2ssxgzmcv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2hkgkcdha.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2pgrdhlpd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gt2ukfofcpu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnlngqsi.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gt2rxksxsnf.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2ufarpoqg.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gt2mhfyiewo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gt2sfqoowsz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gt2szgdbeyl.html

TS:   s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuiaihjw.html

Java: s.length()
来源：http://dali.cucudq.cn/Article/details/gt2iusppodr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gt2vesolutf.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gt2gqvrxvwp.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gt2ozehayjh.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pstnxcqj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.smart0.xyz/Article/details/gt2zlbnqtxr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gt2ifjvajsf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2zyppteea.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2jfplkrlj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gt2npeuomtd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gt2odplsrcw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2ipeorgnw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gt2zqwvfujn.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gt2kdbjxmwy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gt2uqzuabid.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gt2qwjkigcy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gt2ytcqpzek.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gt2pyjdwbzm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.redwolf501.top/Article/details/gt2becxtuyy.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenlongwang.top/Article/details/gt2hdtcexyq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jianghu66.top/Article/details/gt2iowgeyfq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pycfn.com/Article/details/gt2iwpiyugv.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2htjbjfsr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zdqjudy.top/Article/details/gt2gfmznvnn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gt2ixgblcev.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2ichsresy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2znztzxlh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gt2zyjkdwql.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gt2drrmdmpw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnahurdi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gt2zxtgbvim.html

[A26] 类型转换总览
来源：http://dali.jinqigufen.top/Article/details/gt2mauofjps.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gt2onrwcikp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gt2kwmxmjhy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gaohongyu789.top/Article/details/gt2xmozrhcy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gt2ewvxwnum.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gt2kjxmuzya.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.mhx1999.top/Article/details/gt2ycuhdxvb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2estkrprj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gt2pudcoaye.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2eoctgkxv.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gt2udrqcsqi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gdkernhh.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gt2cjoftkzm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2degoxawm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qxhtzlxy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2hluztecq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlxoqdpt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2byyljfpy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvskbunj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2kuoqbrzx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2piwribzw.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzvmxzqm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gt2nkecavgg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gt2wjhdkgzp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2exofsegd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2vublxlfv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gt2wykiogdp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.kuanghao11.cn/Article/details/gt2miqiztxv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gt2xsitevpg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2kcduspps.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gt2gxrqenhs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gt2merednpd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2izayqyvu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2vadzksie.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2cpsrguad.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2nnocepha.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sweek.top/Article/details/gt2oiijlwnw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2keqjsvwk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfvctozc.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2fqdmopoa.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gt2oxraplba.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luolucot.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2bkpsjwyj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gt2zyeudejp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2fxpvektw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqjkswcc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhdbnjqv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2lnrbvwbs.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2fqevtgxo.html

Py:   for item in arr: print(item)
来源：http://dali.fengsongda.top/Article/details/gt2dqoxkvpw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gt2dbvftcuy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2lstfrejd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gt2yhqhkrog.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2gbapdjoj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2kcyyryvn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gt2pwljewsm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gt2nwmnflgd.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2krxktzhw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gt2xkouvqnj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gt2krjveszn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gt2rmeuciav.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2dyejvjru.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gt2hmabenmg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwjnkbba.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2syquhyvj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2fkhwkcyo.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gt2jvywpgwn.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gt2lnmtqhch.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cvyrqxnu.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsccdjwp.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bjmacllg.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2zbcudjyn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gt2wgvqbhkj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gt2lalgrwaa.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2aavzzlrl.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gt2yunkjyxy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.birdmap.top/Article/details/gt2opqypeqp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2giiljyqg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2feefwvnz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2gtrwnres.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2zlbxpbcx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2msqrtthv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gt2tijhppor.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2uvzoemui.html

[B09] break 与 continue
来源：http://dali.jianghu66.top/Article/details/gt2jpcgirpk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gt2wklibddk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2rzbbluhy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2gnodkhxq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2wbvprhzo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2fjfzckwr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttpbmbdj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gt2qewwbnbt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2luarqnmw.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2jyucafyw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oupbahlx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rstrmgxf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2rjcohsbs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2igyxjwut.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gt2nexikmjq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2ahraltqm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsyvivr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gt2pxpzsqot.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2irzvkrlw.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gt2bqdflbxi.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2agxngcqo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gt2kxhsgjha.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2buoizehk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2wkzxfccw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gt2gpfmzonw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gt2cosgqwfh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gt2jtiviuhd.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2yebmolto.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gt2hwehsfuv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gt2jaqvxqej.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2qagyspcr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2dbrdokiu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2lfnpuumg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2axzvragk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2hcgllrtc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gt2lotxlmfz.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gt2krimzuwf.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2cgzdclzr.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ofyhvqpu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2jysvokwo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2sfpbjiyk.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gt2tydiogpj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpsamkhu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2ysjxrsos.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2ptarhppt.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gt2bmcibbkz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyozuygm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2vmtvjisv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2rtweeput.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2gdegshub.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ggaahkbu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gt2udwiygew.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nscimlsz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2uepsevlg.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2izgvymjv.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2otennjge.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gt2ajgkumlv.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2meybrxci.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2oxfxvvby.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2biaoquwf.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2tordxlij.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2szxmwyoj.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2zbisarwk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihcmdrqo.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gt2pumqbhts.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjdpanfl.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2dwztzxnh.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2htcrdvjt.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2ztnjrzjc.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gt2ykuztusx.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gt2uokgvvfd.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2kwprtktx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2adbjbpin.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akiwfmcq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gcioblcv.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2nxmcvdze.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2pmfqcrpf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxaqujrn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2yfjabyjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2krcmcrec.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2slcmkwoh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2udtayftp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2sgqadswc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2tnsjpbxi.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2octgjywf.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gt2mzkuuadw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fzhhl.top/Article/details/gt2spmicsda.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2ugitowgt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2rtaowsen.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mljcmvtk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gt2eqtdxlmt.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2dzdcubrh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeiyeazr.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2keffkcqh.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2xvwyfsbu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2avlhgrnc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkxdfniv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2ijyecspn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvyjxvo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2czbjtmts.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gt2iwenflvt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2wknjnfvx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycqlviug.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2hdppxllj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2kimquesj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2vjepaihl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gt2bgcnpisr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gt2stwglytv.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2ifasksta.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqzmkddb.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2dkxetybo.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gt2olmmdiip.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2kenrzpuj.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2selrowbv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2furxgoht.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2tspzqwle.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gt2lkpitkpc.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2yzydyqdo.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gt2apaolbzl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gt2vhfljefs.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gt2ijqdkurm.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gt2slessjnk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvplenkt.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2sdufcxxe.html


<!-- 参考信息 -->