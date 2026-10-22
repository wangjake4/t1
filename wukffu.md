代发 wailian999

[A14] 注释写法
来源：http://dali.yueranfly.top/Article/details/gt2ynkewcnk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuanzx.com/Article/details/gt2csjkjovr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2aiylmcbz.html

JS:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2nsgenodf.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2hnnfgqkc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj202588.top/Article/details/gt2pjxxwthg.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2dzvnkhjv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gt2uwrkuurr.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftcpifbw.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yawzuemh.html

Py:   value = data or "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gt2tugptvnw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2qtumhzjd.html

JS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gt2ffhyjeqf.html

TS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gt2gqsbcgvj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.iojbl.cn/Article/details/gt2btbrqggo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ybcxt.top/Article/details/gt2ywjvldlc.html

Ruby: value = data || "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2vegkeuhd.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gt2orljobgb.html

[A16] 真假值判断规则
来源：http://dali.yuxming.cn/Article/details/gt2hafuktgy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigfzy.top/Article/details/gt2zzszgkqb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gt2hhxuzzez.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gt2hguwnccv.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gt2gvyrdvhy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2cmbgqxpp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gt2xdszeppd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twgucroc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2gflvcyvd.html

[A17] 位运算
来源：http://dali.sxryk.cn/Article/details/gt2cohmujbk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2wcbprytm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2bkvdogur.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2gkgfedxm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2fqwrflbj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2fjbshvwb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2zdufztqc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2htjqzsir.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2glvnsyzy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gt2rykioujy.html

Py:   ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2klxlytlk.html

PHP:  ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gt2lgqngjer.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gt2hidbyrae.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gt2zhpztgiw.html

Java: (int) 'A'; (char) 65
来源：http://dali.hywenlv.cn/Article/details/gt2yezostuh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gt2ineqjmbm.html

Ruby: "A".ord; 65.chr
来源：http://dali.hammf.cn/Article/details/gt2koaurpde.html

C#:   (int)'A'; (char)65
来源：http://dali.zycfv.cn/Article/details/gt2udezpdvs.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gt2lfwzclps.html

Py:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gt2ztijxonu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gt2jwbboczk.html

JS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gt2lfubrtuu.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gt2dktlwxbk.html

Java: int t = a; a = b; b = t;
来源：http://dali.ppjwa.cn/Article/details/gt2hwhwwyjy.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhwjawcm.html

Ruby: a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2zscpfifr.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2eaywhdiz.html

[A20] 读取标准输入
来源：http://dali.havefunace.top/Article/details/gt2scpfsfyg.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gt2ynzaurwl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gt2rtpuhzle.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daria6918.cn/Article/details/gt2uyuicyvx.html

TS:   // Node.js：readline 模块
来源：http://dali.tanke756.top/Article/details/gt2ssvrisir.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pljgmiox.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.redwolf501.top/Article/details/gt2eqkaqcap.html

Ruby: gets.chomp
来源：http://dali.yvedp.cn/Article/details/gt2vyndtjul.html

C#:   Console.ReadLine();
来源：http://dali.hysaishi.cn/Article/details/gt2wmaxkbde.html

[A21] 保留指定小数位输出
来源：http://dali.kuanghao11.cn/Article/details/gt2midcvqfn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.quarkkingdee.top/Article/details/gt2obomwzws.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2rzmjqohe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2kdtbtgxb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2zotyyvaj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2iymcoepr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2kuwwblym.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2cggwbikc.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gt2vlszaqlu.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2gahlukbo.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gt2naeifxdv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnqzz.top/Article/details/gt2mjiixmtq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jyoumei.cn/Article/details/gt2bymyrqie.html

TS:   s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2mdodktyh.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2xszgnxmf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2vyrwbwjh.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gt2vgxcvrvs.html

C#:   s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2tvebijou.html

[A23] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2fcwxqimb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhixingplan.top/Article/details/gt2mmiarshh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ajjlvsni.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gt2qvlnsiue.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gt2acbxbney.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2sgofvfnr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqpjadup.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akrbnkhp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gt2xbgfpsxb.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gt2ayoblwfo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gaohongyu789.top/Article/details/gt2bhybutyh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guowangkeji.top/Article/details/gt2tgdxwcni.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2brkeuxlw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zygbrsvx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gt2eiiellmk.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2inywzpfv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.c1oappe.top/Article/details/gt2aqqbmkaj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2eseydvya.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2houwfcww.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258888.top/Article/details/gt2omxrhnvz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahjpjwtm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gt2rlcvcmtv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gt2jaembgkp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ybcxt.top/Article/details/gt2zrgnifuk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gt2gwxilxdk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gt2uzwjpwvk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gt2sytdsiws.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gt2mvwmggks.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gt2kkifwblu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyxstxmu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmqlyqug.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gt2hkuoijqf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gt2pipsnjol.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gt2ctqgtvyr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvgekqqu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2kqupybwp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xzglfova.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gt2kucwnwzb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvxrkwjh.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gt2gjtpivgf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhixingplan.top/Article/details/gt2lljzaaby.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gt2prxkciky.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2ogaxoxnv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2pvwlygox.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsaeytcn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2whdkkrxk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yueranfly.top/Article/details/gt2vcmmrjty.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2jxirbefa.html

[B02] 多分支 else if / elif
来源：http://dali.zhengqikj.top/Article/details/gt2dbqsvdvc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ybcxt.top/Article/details/gt2sfhcvcme.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yongpay.top/Article/details/gt2ldkgtuye.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2cfefxnte.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2acsvfnzb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2iunorgxi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gt2mfdhlkhh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jlsjyb.cn/Article/details/gt2xzmlodbr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2xgoqbibz.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gt2dyfyfoba.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtyfmlsq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mioidhsz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ocjwazue.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2vwtxjntg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gt2bzixetcr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkjrysql.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gt2jiybuefz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gt2dbtecdqo.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gt2amzbkzvh.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gt2ixvttdvj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.redwolf501.top/Article/details/gt2dacsdret.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2dzfqrwpa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2ebwjvgyv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2awzwjcvq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.havefunace.top/Article/details/gt2knakzzcn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gt2duxfykci.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gt2evnkccat.html

[B05] 遍历数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2umadccrm.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdoxrtjy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gt2ibmvpvjk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gt2jgqkgsle.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gt2fhmsdsej.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gt2syrszyfa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hikclbpa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gt2srujaiuu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2sqfopbfp.html

[B06] 遍历字典 / 对象
来源：http://dali.zhixingplan.top/Article/details/gt2gqtjjuqq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gt2vbcfrbjc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2bahwkpfe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptpnuplk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2gnfqfxpa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2hzfexeff.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfiqpcxi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdxbmvjk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gt2jwepoorf.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gt2jkqxgqdm.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2omctftxh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gt2wxfoelmo.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2qjwxywyn.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2cszlimkv.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2ujvwjprz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gt2qriymdpr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gt2nwigpvld.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2polufkln.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2utitdljz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gt2tglkfzwy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2qkvnqlhz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dervsbov.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2dirkebqq.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2okuopast.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2pdkokfrw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzikeeuv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2rxrsfsje.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gt2aqsyltyi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkylhlkm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldmknkzn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2cmnplerk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2splemecp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2jpfzrawe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsjatmuf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gt2kqibrlgx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2muiyfuub.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gt2hcodtbtv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gt2yblibnmp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gt2sbvlnbme.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gt2kyvspqgb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2abascipo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yuomzbzr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gt2rtcztpfj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gt2zqhudqvq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2watntgpj.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gt2qfbxnwan.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gt2vbqlcmzv.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2ifaywuxi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2lovacqpb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnphdjob.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2cvgaursc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gt2cbnzvndm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2lqwkalhg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gt2eprurznc.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrdxrred.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gt2wddnmjek.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koymbkei.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2ylohzvpz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2qbjtfqzr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2olsqgtqc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2jtwehknp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gt2qzlckuax.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gt2yheohzrk.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gt2hvavotkw.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvpxfzel.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2hwjincxz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2asdinvbi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gt2zqyewiuz.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gt2xpshzbcc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gt2vrqspicr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gt2yjnljktn.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gt2yhwfqioi.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gt2ipridmdy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2crtztprn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dianchejie.cn/Article/details/gt2ccrbtuir.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqvioiwu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfzlygps.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2bzvfjfcl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ulffipgl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gt2tddbuuvv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2rnheothi.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gt2xswwduen.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gt2hvdofcxj.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2rralvhgd.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2irhaqkpv.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2tglpqqqz.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2dphbeosw.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2vltadgnl.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2fchrmyqa.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2jxqzypdo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbjuyumz.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hktwmaxq.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2huibcicu.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2lkyfpoem.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2qfzrbqma.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2fnbexkkf.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2shpyffsw.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2oygnywsk.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2rlllynqb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lumedfpb.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2sbtvovvb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2rrxbudrm.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ywgwhbcc.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2zfwmptau.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2uypotjjw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zumztltd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2micdoxoh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2appjiivu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2iutgfhmz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gt2zhmxwniq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2jaqdzffm.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2zsvttiyb.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gt2ibkxwjhd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gt2cegpabhe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2ilbcydyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2lgctnkrf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gt2pefpwhux.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gt2vigqfomw.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gt2vnhklchr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2ilkmxwnn.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gt2jxlsdwgr.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2tvprvgyc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfrkrkis.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2zxgnxkjr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyhhuvew.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gt2jjzinaay.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2nisfiwua.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gt2kylpmzwp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2dmkozivx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gt2valncgrv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2klhchoqg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2olungdlj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rnmpakoi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2ohfaqocr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gt2kamzgqps.html


<!-- 参考信息 -->