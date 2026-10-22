代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.0kj1m.cn/Article/details/gt2alnshpds.html

JS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gt2adxytpkr.html

TS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gt2fqbqzjzh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hammf.cn/Article/details/gt2bhyjldhu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhengqikj.top/Article/details/gt2prqlduzi.html

Ruby: "Hello, #{name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2qoglyxca.html

C#:   $"Hello, {name}!"
来源：http://dali.quarkkingdee.top/Article/details/gt2bytqovxh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiwpvcxa.html

Py:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2itcmkhkk.html

PHP:  "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2xrjmnqgr.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2zdmxbpge.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2klzedtnv.html

Java: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxflxzmn.html

Go:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2nzfdomem.html

Ruby: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2liesjhpd.html

C#:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2vkvmfvvm.html

[A14] 注释写法
来源：http://dali.yvedp.cn/Article/details/gt2jmiqwcby.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tian-w.cn/Article/details/gt2jctjrmfb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2tdwzgbmy.html

JS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2jtukdvte.html

TS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gt2bngxxrxi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gexacndv.html

Go:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2rvsomvnz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tianlin.xyz/Article/details/gt2dlmsdbgx.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2fpukgrpr.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gt2vccatyhp.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2xqyydaho.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2goqxdhev.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcygfwql.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gt2rzeoxnux.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhoulong.xyz/Article/details/gt2bccfrgac.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxinkj.top/Article/details/gt2seotkoio.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gt2ycewejvx.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2izatunzx.html

[A16] 真假值判断规则
来源：http://dali.yangfankeji.com/Article/details/gt2lulucncx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2clobmzeo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gt2mbreymzf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gt2yhksnuml.html

TS:   if (!x) {}
来源：http://dali.pycfn.com/Article/details/gt2tbinbxez.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xziqi.cn/Article/details/gt2sjxfcyoy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.havefunace.top/Article/details/gt2umlhdlim.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cdnleiting.top/Article/details/gt2fsviomqf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfibpupm.html

[A17] 位运算
来源：http://dali.jqgfzy.top/Article/details/gt2rmkoxyjs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2mjuzhfub.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tanke756.top/Article/details/gt2igzqnqml.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2itzzcqom.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2uskugstr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2itixihmc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2wophujpg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ouddpsum.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2mlcktezz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gt2tvwvopfx.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gt2vfytvgqf.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2aomqkerz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2gtffqmgj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gt2onfwkuuk.html

Java: (int) 'A'; (char) 65
来源：http://dali.sxryk.cn/Article/details/gt2znauhdxp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.bjfxy.top/Article/details/gt2wpxurvxo.html

Ruby: "A".ord; 65.chr
来源：http://dali.hammf.cn/Article/details/gt2msmeofvt.html

C#:   (int)'A'; (char)65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntqanbds.html

[A19] 交换两个变量
来源：http://dali.yuanzhike.top/Article/details/gt2vzpprqtn.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gt2perofayc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gt2kzohqsiz.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gt2bhyvvbvh.html

TS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gt2rudmrbgd.html

Java: int t = a; a = b; b = t;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlwfrouq.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gt2wpxzqsvr.html

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2umjrpmbo.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gt2fefxyrcc.html

[A20] 读取标准输入
来源：http://dali.jqgfzy.top/Article/details/gt2wcrplubw.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gt2psutedik.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yonumen.top/Article/details/gt2ocnyfoiz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gt2vxybdsvu.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2sgruieap.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.kuanghao11.cn/Article/details/gt2fsaouzrq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gt2omgexacs.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gt2dqgfxexa.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gt2tlmowlgp.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gt2nzdngopn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yonumen.top/Article/details/gt2swutobfy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwcfnixe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2nzzybebq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfvhrwg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2fndykdyr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2npyekosj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2dlxsvyej.html

C#:   3.14159.ToString("F2")
来源：http://dali.ydzc1.top/Article/details/gt2ljrmbmtn.html

[A22] 获取字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2ersyhiou.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2fsluenhd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.snrcjt.cn/Article/details/gt2pimkjmsh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gt2glcoxymu.html

TS:   s.length
来源：http://dali.yueranfly.top/Article/details/gt2aplxujel.html

Java: s.length()
来源：http://dali.yonumen.top/Article/details/gt2fykeqrjk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hogdanfe.html

Ruby: s.length
来源：http://dali.tianlin.xyz/Article/details/gt2drkyxvyr.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gt2xcbbskhk.html

[A23] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2eiutygem.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tanke756.top/Article/details/gt2xoghmnhh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkfpzqva.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2bdzmlduq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2pqkwftqi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2pqrysisd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xyicxoco.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2iogaojyq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ivvv.top/Article/details/gt2nlekeeiv.html

[A24] 去除首尾空白
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsbflyka.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gt2yeesvpdx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jiagoushi.top/Article/details/gt2zelmkeof.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2xsomugon.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2sdhttgtk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.bjfxy.top/Article/details/gt2hipglvti.html

Go:   strings.TrimSpace(s)
来源：http://dali.aibaodan.cn/Article/details/gt2insnhfxs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gt2kybeijju.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2pytqnpzh.html

[A25] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2ltnjsfuj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gogol.net.cn/Article/details/gt2fwyuyztv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gt2xxtkgrua.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2zyhqyqnn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gt2nhqdcnyh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2bblpietc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gt2iypgehyl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgfzy.top/Article/details/gt2otxnicew.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2glleyuwv.html

[A26] 类型转换总览
来源：http://dali.yanxiufei.cn/Article/details/gt2fiazximm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guowangkeji.top/Article/details/gt2mlxzpcxf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gt2lwnmemmx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj202588.top/Article/details/gt2tryywwxt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnqzz.top/Article/details/gt2llawddqi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gt2bmjgnzzs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pycfn.com/Article/details/gt2juongrdm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2uuhcjcvn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2azgkvrgr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cguctxgf.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gt2waczctzl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2eqamvotp.html

[B01] 条件判断 if / else
来源：http://dali.jqgufenzy.top/Article/details/gt2jmdrngsq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2bxjelusc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gt2nulideki.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gt2xgaylrbi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2vptuvjma.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gt2wrzaqoyq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gt2tdpnhilu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gt2evgsufqx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2vbsusofs.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gt2eandfqxn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gt2nkvyvtdc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ivcbqkwj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2cghurssd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2iszlolpp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2xrnaijmz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2htcmsgss.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gt2utqdzjtm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2urngxols.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gt2uwuukqzc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxaddtbw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2aqekqycs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pxysrwkh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfwxheyj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2azgwujkp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tezxxled.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gogol.net.cn/Article/details/gt2kijclhuw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gt2leozrhxv.html

[B04] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2zdkpzndi.html

Py:   for i in range(10): print(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhrzpleb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ivvv.top/Article/details/gt2zukxxdea.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uljwgmvk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gt2znwkfwqs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guannengcc.top/Article/details/gt2dmwvoduw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gt2uhfyquxd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxgqyfkh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wumuvemb.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzsjlhig.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gt2ysnrfrtw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whlldwrt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xwwfypjn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zuavcujd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2knhdeksw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzijrmgx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gt2yqspdwpz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gt2gptefkzh.html

[B06] 遍历字典 / 对象
来源：http://dali.sweek.top/Article/details/gt2ufaztkog.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2yriojlqj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gt2guygrjna.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2guphedxm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fosfopco.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gt2prehwrqj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gt2qinkloxm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gt2onvtvvix.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2bjzqzzni.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gt2yeuaidqo.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2vwvtimlm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2jaobahzg.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2pzrdkcej.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2ztevzamc.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2xwjhpknm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gt2kntfimtv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2hfheksvw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pidxpzsu.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gt2xcykgbrp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gt2ucmozwxa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlnxgrkt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2qdfdjmqr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2ucwdlujv.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2efynzhad.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gt2juqegkha.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gt2hlbkryzt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2teqhktdw.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gt2tsvzgyov.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gt2jrziathm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bniqtpjv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2afzacvgr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2vhktmedc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2melvhyvs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2iulpupic.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gt2jjjbxvmu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2xoywsnwo.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gt2vkwsravg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gt2svexlpjf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvnqyzuk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2czlqujmr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2dauivtbd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gt2bvgkowya.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2pighmrjc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2wrkwzuwn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2wvowqasd.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuusostb.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gt2dpwoyhjm.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2tnembbqu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gt2qkekpwmd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2mowhzuym.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2buouyftw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gt2hzfptyxb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gt2mtazdnwt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2aoymragw.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gt2vkynsgjh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmsqaxxc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2lauhfuzz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2ewupjppx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2hxhinepz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzfqrpku.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gt2lzvonjxz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gt2uwyclzcp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gt2vllynukc.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gt2lklopqop.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gt2dfaqrhfv.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gt2gvubjbcq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2dotatmcm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2acgfwefh.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gt2dhauekxz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwlqsfpj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gt2saebwmgw.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gt2gxjeukxi.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gt2cwrjbzsv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gt2jlzsqguv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2ugbwqkya.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gt2ktznyngt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqxgkrtr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2lkgepvlo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2klmyqqix.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ibaiqngh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ujczudkl.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gt2tywecvfo.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2pjqqquan.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gt2myknjauo.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2zpkjroex.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2bbssgmiw.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2anbxbcks.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2nldytwbl.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2imbaetyx.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2mehxdcmu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojxtwzhx.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gt2tsrymwjw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmnpevut.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2emdnjybr.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2kbjqbvqc.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2ckdgtfof.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gt2motrldlr.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2gotylgmk.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2dnckxyjq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2wcqlmyne.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2syiilgqg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sfvdbaei.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pedgrjnk.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2eqvkflpz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2nadmkygu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2bgklvwti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2utqdeepe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2pbajbdoi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gt2pkzpqzho.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gt2qsnuktgo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2wyszlngz.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2gjuhuisz.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmianrzo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2feluxhmz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2hdacyivy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2hryotvgn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpsxdaik.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2rtovnlcv.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuqwvkzj.html


<!-- 参考信息 -->