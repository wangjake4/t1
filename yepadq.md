代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigfzy.top/Article/details/gt2dywoiftu.html

JS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gt2hjfgfmbu.html

TS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gt2xcrfyjza.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pycfn.com/Article/details/gt2vrfftlfl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cqqwz.cn/Article/details/gt2xvxtzmju.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuanzhike.top/Article/details/gt2alnjtwcd.html

C#:   $"Hello, {name}!"
来源：http://dali.gotoacloud.top/Article/details/gt2asmytrsr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj202588.top/Article/details/gt2pnwhpklm.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2pljytphk.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2tbbpdpub.html

JS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2lijacmcr.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2nnkmqrif.html

Java: "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxbsyeur.html

Go:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2lmftscku.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcouiosq.html

C#:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2badjocjc.html

[A14] 注释写法
来源：http://dali.feifeiyinyue.top/Article/details/gt2atkojuuo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.meibo888.top/Article/details/gt2ikmqagdc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gt2hyefzymd.html

JS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2vyzhmhos.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2qfzipahy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gt2mvpcdsls.html

Go:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gt2ohkwoqlf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.316326.xyz/Article/details/gt2axeziifo.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2dnrujrxe.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gt2renkjkdj.html

Py:   value = data or "默认值"
来源：http://dali.hysaishi.cn/Article/details/gt2mgtqkiki.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gt2tmtwnqpm.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gt2xuxgzmoa.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyzflcbx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gt2vappcbqy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tianlin.xyz/Article/details/gt2wkiyscti.html

Ruby: value = data || "默认值"
来源：http://dali.snrcjt.cn/Article/details/gt2cnbbjuav.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gt2cgurbkfw.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gt2oqywhdfo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2zrnniica.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gt2ksmjaeih.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.andypj.xyz/Article/details/gt2xjdzbujm.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gt2enqkmvox.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gt2sekvnmpv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrxfbiww.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxjanlqa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2sidcacvj.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkdisqru.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2hgkkfcmt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2cifscajx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2lrcsfvmb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2bqwcxlwh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2dfxbnhxy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2wgvgprmj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2wwpkbvhg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2scwdjanl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gt2tqveilze.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2ndlzoitd.html

PHP:  ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gt2szbuhyhf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2gqtobfiz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2jlcufttc.html

Java: (int) 'A'; (char) 65
来源：http://dali.aizwys.cn/Article/details/gt2gwulftin.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.snrcjt.cn/Article/details/gt2waxjmqyz.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenlongwang.top/Article/details/gt2gjkxskqr.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gt2pxpxgpzw.html

[A19] 交换两个变量
来源：http://dali.bjfxy.top/Article/details/gt2xwxrnsho.html

Py:   a, b = b, a
来源：http://dali.yonumen.top/Article/details/gt2oicmipqp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daria6918.cn/Article/details/gt2svoppsja.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gt2ccimlxbp.html

TS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2dhptzytf.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gt2tyzucjps.html

Go:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gt2rercdqek.html

Ruby: a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gt2huwissgt.html

C#:   (a, b) = (b, a);
来源：http://dali.ivvv.top/Article/details/gt2ttzrefgu.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urxrhniw.html

Py:   name = input("请输入：")
来源：http://dali.jlsjyb.cn/Article/details/gt2vblboqmk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxaqbqpy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cdnleiting.top/Article/details/gt2qucthiiq.html

TS:   // Node.js：readline 模块
来源：http://dali.hammf.cn/Article/details/gt2agabliko.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.meibo888.top/Article/details/gt2hfqhnwkf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gt2ifpwmmvv.html

Ruby: gets.chomp
来源：http://dali.havefunace.top/Article/details/gt2iuaviwnv.html

C#:   Console.ReadLine();
来源：http://dali.zhixingplan.top/Article/details/gt2qlkgnkyt.html

[A21] 保留指定小数位输出
来源：http://dali.mhx1999.top/Article/details/gt2hddqljen.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsfvbfy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gt2eqeogpow.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2otnwnprk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2tflcfjab.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2uzltvjaa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2szqtkavv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2cwvquknj.html

C#:   3.14159.ToString("F2")
来源：http://dali.9152youxi.cn/Article/details/gt2nahkhxjj.html

[A22] 获取字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2cifucevr.html

Py:   len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2qwjacvix.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gt2sdtjthro.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cheryme.top/Article/details/gt2evugjyax.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gt2xkkghiuq.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2stmlvhmt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2grrfpfih.html

Ruby: s.length
来源：http://dali.0kj1m.cn/Article/details/gt2ehxndwao.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2sehrenva.html

[A23] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2ktmdudag.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gt2tknogpsv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gt2prmsailm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gt2quysjpev.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2dhckyhke.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2zipnfqoy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gt2wvvfukjd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2nvnqbbel.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gt2zozruuml.html

[A24] 去除首尾空白
来源：http://dali.ivvv.top/Article/details/gt2lummqwmi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouwtsaca.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gt2buqxinhb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isghshgs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gt2okzvattd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gt2wkcvukbs.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gt2ufiwlabb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gt2yygxqynv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2hbovyoyl.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2xmxyarqm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.svipenyu.cn/Article/details/gt2yczgspmh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hammf.cn/Article/details/gt2qovusrqb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gt2aluyofjg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doziqljo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gt2cbycplaz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gt2sbbgtsdg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gt2dvijxeuy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gt2sdhbtrcl.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gt2wbseiykl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gt2jfhtqyuf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkafffcs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxuanxn.top/Article/details/gt2uodqctzg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gt2zgwzprtg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gt2iogckfol.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gt2pkuuphdc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gt2ttzmvlje.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2jantcvpx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2wdvuezhc.html

B. 流程控制
来源：http://dali.aizwys.cn/Article/details/gt2gndfnxhi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ndwdjosc.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gt2ctzvwjbz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gt2cixghvwf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkdmlnbt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2lvatryfu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdpjtcsf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2xvogmrfj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gt2fsjjpxos.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gt2xdflmseo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2zutbdnwj.html

[B02] 多分支 else if / elif
来源：http://dali.fzhhl.top/Article/details/gt2pkqpzlug.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daxiang520.top/Article/details/gt2iiefjnvc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkydkdgi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2ladkofsf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2wsdupwus.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gt2uhgethel.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gt2jdqqzczi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gt2mfpfsqrn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2zejrhjbm.html

[B03] switch / match / case
来源：http://dali.cheryme.top/Article/details/gt2upcwykhu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwlluplq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuulrzqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2btvxdoqf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2vdnzpbtd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2iahiilbt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czjlmqua.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqmtqehv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gt2cneyqngu.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2yblatvnq.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2mmmxbyfr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gt2znrldwio.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2sjoqhqeb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gt2ljcjbmag.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gt2weburbhe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwseyumz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gt2prozafcy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2etqluwgt.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vozjntip.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwlzjigj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rruxmwnl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gt2ibndkype.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gt2rmmovggd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhlqqzkr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2esknffff.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhmkihvx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gt2osttvnhg.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2smizprik.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gt2ytldstkg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gt2igmtaoya.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gt2yeeotkql.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2cmdvgbbf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2fdoweerj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gt2imqfcovx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gt2zdemcyyr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aizwys.cn/Article/details/gt2gyqqyfjo.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gt2mixaghko.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2kvaklrpm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2shgqjisi.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2oopdjdse.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2xrtpojas.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2nqwuhajk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rineqxbh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gt2mvpzdfqa.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulrwmlli.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gt2hmphwfos.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gt2uihvhxcx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gt2neiukejs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2objpncis.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixdtqkvu.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2bficenfr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2lsozsflg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gt2jpxahjxu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2bebflcjy.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gt2pdinaxyp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gt2lriiahrw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zfwseiti.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2pjfdebdt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2lzkyvcoy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2kcjasopu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2tjbzuyin.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gt2wkssmkck.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2mhnhxpsz.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2hywlvkpk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gt2ocenynch.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2ekuirfve.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gt2uutwndzz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2ifrbecpc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zizueicp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gt2ucbqdkdd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gt2uuizmkyq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bjnahpjq.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkusazgh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gt2tiiiwacm.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gt2hfqpooaz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gt2tdtqolsm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2llzboldp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2onjbfrmv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cheryme.top/Article/details/gt2wkyuxlpq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gt2wblvqpeu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dwpfzwnk.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gt2tdgccmnx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gt2zcdexmse.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gt2dilekqtc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2srvpccch.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2cfdczwxj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2nvvzcmsm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gt2zjlkpntk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2lupbckhr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gt2xeqjdeuc.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gt2yyfuysye.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfgfuhed.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gt2egnrwvag.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2zwjfzxdr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gt2zwwwiamr.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gt2jpfsgzvu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gt2zadxdias.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gt2buxvtvnv.html

C#:   x is int or double or decimal
来源：http://dali.hfpthk.cn/Article/details/gt2lhhwruac.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avrddegx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gt2peipmbxe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gt2fuktdyik.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2kntfbqtv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ugktrgao.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qpbphevx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fscgcocp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzazecnf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qajzjiou.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmoujaam.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2lnhspyun.html

PHP:  $a && $b || !$c
来源：http://dali.gogol.net.cn/Article/details/gt2gqvilaqn.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2fhjobyae.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuxbeqpj.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2clsvrfem.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2hgwzxckn.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2fiilijbl.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2erhjxoyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2pepcammx.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gt2kwbxpxbc.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gt2kdgnlkiw.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2kcmuchfm.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gt2lqrlupxn.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2hytfawve.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2pgjfzkdt.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2bkygelie.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boymanxw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2blzrpqsc.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2otbzkaqe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zlbndfec.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2rpezrjnz.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2ytdtlarx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyhjqvxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2kdtjzsmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2xndxjyqu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2ckpienld.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2ffdydcia.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vghkujdo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2xiequofw.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gt2sjbvzbof.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gt2eeauwflj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gt2wbukujve.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2mdeohzig.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2zlfmmazm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2yscjrqak.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gt2tyuwkfft.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2okebvpuu.html


<!-- 参考信息 -->