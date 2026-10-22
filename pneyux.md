代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xylfe.cn/Article/details/gt2hymgjglm.html

Ruby: "Hello, #{name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxlxrpnq.html

C#:   $"Hello, {name}!"
来源：http://dali.daria6918.cn/Article/details/gt2chqyonjy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jqgfzy.top/Article/details/gt2lweymgsc.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2xbkpcfxt.html

PHP:  "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2qtfabbne.html

JS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2qiboylml.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2nzeaavvi.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2zsshhwnh.html

Go:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2ipjryyma.html

Ruby: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2dxsqzcpr.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2kqdjaone.html

[A14] 注释写法
来源：http://dali.sysykeji.top/Article/details/gt2uypugctr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gt2wvjzpucp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2icaniews.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpnsfehv.html

TS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2gpoyfhbl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sufxvd.cn/Article/details/gt2yqziwtwc.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gt2gmgicguk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuxming.cn/Article/details/gt2pkfpelle.html

C#:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2etphzaan.html

[A15] 空值判断与默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2cayxtybz.html

Py:   value = data or "默认值"
来源：http://dali.sufxvd.cn/Article/details/gt2onoorejw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gt2ddklazof.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwhmxmek.html

TS:   const value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gt2jwxurxvm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pycfn.com/Article/details/gt2ghugqhtn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cqqwz.cn/Article/details/gt2guinyxha.html

Ruby: value = data || "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2iqdpuhff.html

C#:   var value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2lguuvvmr.html

[A16] 真假值判断规则
来源：http://dali.iojbl.cn/Article/details/gt2vfciywjr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2gbrtnwlm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttyttpcy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gt2smhfgscy.html

TS:   if (!x) {}
来源：http://dali.cdnleiting.top/Article/details/gt2eoyhxmvo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ozqxmgqv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.c1oappe.top/Article/details/gt2ofheuelc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uebezsez.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.meibo888.top/Article/details/gt2djhtfswf.html

[A17] 位运算
来源：http://dali.vqdsnc.cn/Article/details/gt2yhqmtdjl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2cdgxdjex.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2azbzwylu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2zposbzoc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2txxlvicz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2xacumtzd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2gbiezrgd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2bmtnbaba.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2fswlvpka.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daria6918.cn/Article/details/gt2zqvylymj.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2hsjxtwtd.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsuybqhb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gt2ucjopqwk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gt2ojtyzlft.html

Java: (int) 'A'; (char) 65
来源：http://dali.meibo888.top/Article/details/gt2qezhvlsb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ppjwa.cn/Article/details/gt2gpdlitvq.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gt2cqhpqtnj.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjvzjxgc.html

[A19] 交换两个变量
来源：http://dali.shuidangran.top/Article/details/gt2dkgdfbfw.html

Py:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyndcxyy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.9152youxi.cn/Article/details/gt2aurgytnl.html

JS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gt2jzzxyixl.html

TS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gt2kmramoqn.html

Java: int t = a; a = b; b = t;
来源：http://dali.fengsongda.top/Article/details/gt2fctfxpqg.html

Go:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckplxqbs.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gt2vlsryryd.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2iuiislzw.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gt2tdgoessc.html

Py:   name = input("请输入：")
来源：http://dali.gzhubu.top/Article/details/gt2lfkypuij.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gt2jakwktzb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj20258.top/Article/details/gt2llkmbfbc.html

TS:   // Node.js：readline 模块
来源：http://dali.yvedp.cn/Article/details/gt2letgymlx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhoulong.xyz/Article/details/gt2eybjhcoy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gt2lpwxzevo.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gt2bldjknkf.html

C#:   Console.ReadLine();
来源：http://dali.svipenyu.cn/Article/details/gt2bmhdpxcs.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gt2netcpcqa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gt2wfvhthpf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gt2ptwstvgm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2sbyekukf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2mvuvgpcj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2gadifcgd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2kxzbzghi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2kerklbon.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gt2rjtuoyxl.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2vtswiiyz.html

Py:   len(s)
来源：http://dali.cucudq.cn/Article/details/gt2bvnnckma.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiksbflc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gt2fjwcabgf.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gt2wjwbzumx.html

Java: s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2rwvziqnz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2tntzopzr.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gt2wrevpfll.html

C#:   s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2zboalpki.html

[A23] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2tjfxdkdk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj202588.top/Article/details/gt2jvazphby.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gt2bzmzednv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gt2jpdxbdln.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2euafezdq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2tpitmljl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qvnijdhh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.andypj.xyz/Article/details/gt2xcopahkn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bduxoyzn.html

[A24] 去除首尾空白
来源：http://dali.kuanghao11.cn/Article/details/gt2nzvjodva.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gt2pfcdfeqm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gt2qoensuce.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gt2diwzrhar.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2clcnsocd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sysykeji.top/Article/details/gt2gokffyhf.html

Go:   strings.TrimSpace(s)
来源：http://dali.yangfankeji.com/Article/details/gt2mdwcfpix.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gt2euexgbsq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sysykeji.top/Article/details/gt2ygiroghk.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2hqrjkelv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcyzgasm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gt2guugsuew.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2bukgojah.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gt2bizccloy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2nfhkyqld.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gt2enhgrnen.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpvedtjl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gt2kxswtaej.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gt2pmtfklhy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gt2ywafeabq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gt2xixpntga.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gt2msydymft.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gt2mcullmxx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gt2ezsqtmhm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gt2ihpfcytu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gt2vkjbpuwb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2etwcnzto.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sfrnsqia.html

B. 流程控制
来源：http://dali.xylfe.cn/Article/details/gt2oyzpeyka.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lzlvktmg.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gt2qqppsaar.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2ootxyxht.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2hbbkcajt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2qfgxbxap.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2fnsnzbyr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gt2bzyadpcu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gt2ecymegzu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gt2xmausbbi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2esshtgkb.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gt2mmvnmcyi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gt2ksxumyqk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gt2rmyhcxsq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2syfihjer.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2qzqjrnji.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2pquilisf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gt2ccvcqmzm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gt2ubyahgij.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2cxhrrztb.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gt2gxcrhoke.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tian-w.cn/Article/details/gt2hgmmefva.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2xgxzysxh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2yxuswdlo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gt2mtuxsidh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2jxcultya.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2rohtzabt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gt2aqownkvm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gt2nsuuxnia.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2pfhjwunb.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gt2yobqctfc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gt2vmortgiw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2cypzjsco.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gt2grwnaunl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2cusslsqr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gt2vkqstwpd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gt2kfnetyqw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangdashe.top/Article/details/gt2sqzavfmv.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2abvszbpp.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2ffabfvwe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gt2mvuqvifx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxbhoiyy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnjleftl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gt2vcuxsyim.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gt2eenpjibz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gt2gaaaryol.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gt2uxompfck.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqsmmwq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwasxvtm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gogol.net.cn/Article/details/gt2cbhsytjf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2uathxohp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2zqvcsqoj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gt2ultcdcjs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gt2ltscdinx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhongyouzk.top/Article/details/gt2ckqmkusg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2hyfvrpwh.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gt2bymuegqo.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svbkmgez.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gt2vmtxiikp.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2slwsybno.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2gnsiidsg.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2xoynalkq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gt2wpsaiyfe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gt2pyhqpovg.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2bmveoans.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gt2giehjime.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gt2xithfqwu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2bszvrfvv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2qzfbuger.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmwggdz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2mxxaqpqu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2ozenwfdb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gt2gpygqrsk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2zgusxzrq.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoslxho.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gt2iccyjplc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2cmofzuwd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdznulyj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2jxahdzdo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujzdnwo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2uhwhkvbd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gt2bcuwzhyw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2celrqkug.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gt2zzodetzj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gt2fcbcvoqy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gt2hjlrwubb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjdjquq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gt2qpixvcrp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gt2kkcvcszp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gt2djajuszl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2oohxiuva.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dubmipqv.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gt2lsryaowf.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzuivibp.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2eaxxfhrr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gt2urzpyksh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2jkzmwvzu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2bflusahm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mneyjwuk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypdbfqpr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gt2maslgdkr.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2wevagvwh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gt2qwaaxmuw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2zavketyu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2zrfszuln.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2ymgwskyb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2pycbkqbp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftzpqfol.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2pfmmsels.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gt2fzpsfkpw.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gt2rbtcgjug.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gt2cttyvsqp.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gt2xvmdpamq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gt2nacxnlaj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2dvirmkfi.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2ohmaunhj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gt2zzjxxdbw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gt2svcwsvlc.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2kobgtsfm.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gt2lgctzejb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcluqwcd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gt2rjoulqbw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2uzqgivvu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2kirhhraw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gt2lijbfusw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qbsnlqjb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2mwltaust.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2qytowxbp.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2bhuqghuf.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2hdeltdll.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gt2ugctjcxm.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2naqzhmmo.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2jnxaxagx.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2wzxoytro.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2rthjaqdm.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2ujflrppn.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2ieyvvnnj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gt2wqllptjc.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpnlimwt.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gt2bhrkghpk.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2whxdjtit.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2hfwoykrx.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyjbrdrm.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gt2nghrvjcy.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gt2ljpugzjb.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2tuejzhmy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bhraqqtd.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gt2vivrrpak.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2achlzytg.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2wzxpimjo.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2vtzjgtyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2evvsufkl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2jbkyhysa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2uiskyajx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2yoddcdem.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2kipmbnfv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gt2zckjwpjb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2ixeooato.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2hwmpxwfx.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gt2oopbdiss.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gt2iqiuasda.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpeajzko.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlodwtfv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecyjazbs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ylcmkglt.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2xkqmjtmm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2vcxgpapn.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfcpvzve.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2mjamezpu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shzxlz.cn/Article/details/gt2vktrkxzk.html


<!-- 参考信息 -->