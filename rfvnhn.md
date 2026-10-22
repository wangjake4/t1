代发 wailian999

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gt2uhqbkove.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2kbogcwgt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfozqfzh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hammf.cn/Article/details/gt2pqdqskub.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2vyfqjtcb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2ominftzk.html

[A12] 字符串插值 / 格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2esuboepx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jlsjyb.cn/Article/details/gt2geciiadq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jiagoushi.top/Article/details/gt2ufvrvjfl.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gt2guncwfss.html

TS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gt2bnsfzjrb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.meibo888.top/Article/details/gt2yrcclnff.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2fpmbuaqg.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gt2otoxrnlu.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2cimxmdsh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtwxoqdi.html

Py:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2qtgoolqg.html

PHP:  "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2imynlkql.html

JS:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2biksxzia.html

TS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2kxcffaiu.html

Java: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2uwxetbtk.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwsehixo.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2whwsrfaa.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2wiusuikd.html

[A14] 注释写法
来源：http://dali.316326.xyz/Article/details/gt2osnnvsnz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yvedp.cn/Article/details/gt2dxviezrv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2jijllmsu.html

JS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2uxfieswy.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2uhozmfif.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwxonroz.html

Go:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2kcgzdvhi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gaohongyu789.top/Article/details/gt2mxvhbwlb.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2wlgddake.html

[A15] 空值判断与默认值
来源：http://dali.mhx1999.top/Article/details/gt2qykpjkyg.html

Py:   value = data or "默认值"
来源：http://dali.dashuyun.cn/Article/details/gt2spqrwdth.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtonfauk.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gt2zfncmxqx.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsmrcmbe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.havefunace.top/Article/details/gt2hsobtntq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gt2ketkgzsv.html

Ruby: value = data || "默认值"
来源：http://dali.zhengqikj.top/Article/details/gt2vxqwnmqs.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2zpksrzfv.html

[A16] 真假值判断规则
来源：http://dali.quarkkingdee.top/Article/details/gt2tcjzjagc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sysykeji.top/Article/details/gt2boygezfs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.0kj1m.cn/Article/details/gt2bokdoluo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gt2opogigdh.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gt2unznsbyu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ftawhfqr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sysykeji.top/Article/details/gt2pyrreqcs.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2sdqbsgyt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqrbthgn.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2xjpqtmsd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2rudgkyvi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2pnmxauyk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2pprmssxh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2nwnzrrri.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2jogiefms.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2yclugllr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2ladddsyu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2yaqtlnyk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ivvv.top/Article/details/gt2ftogpsoy.html

Py:   ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gt2seavyquf.html

PHP:  ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gt2yueilucb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gt2sfeimakj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gt2qhvmbhme.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gt2qvgdslfk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ydzc1.top/Article/details/gt2zdsafvvi.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eipblnyt.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258888.top/Article/details/gt2igvsrxeu.html

[A19] 交换两个变量
来源：http://dali.9152youxi.cn/Article/details/gt2gapzhovo.html

Py:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gt2dxdthgwj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yonumen.top/Article/details/gt2cdlhishc.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gt2qlgckbwe.html

TS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gt2haysgbfv.html

Java: int t = a; a = b; b = t;
来源：http://dali.cheryme.top/Article/details/gt2szxiflog.html

Go:   a, b = b, a
来源：http://dali.yj202588.top/Article/details/gt2fqndycqu.html

Ruby: a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2pqjmpoph.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gt2flvvtdrw.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gt2vwflaggv.html

Py:   name = input("请输入：")
来源：http://dali.redwolf501.top/Article/details/gt2mtrmaztp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jiagoushi.top/Article/details/gt2rdiilpen.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yuanzhike.top/Article/details/gt2aghpjsnw.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gt2msnstvry.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gt2knhytvfz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gt2buewanez.html

Ruby: gets.chomp
来源：http://dali.zhongyouzk.top/Article/details/gt2nvtpvrma.html

C#:   Console.ReadLine();
来源：http://dali.yj202588.top/Article/details/gt2ghlwukwm.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gt2zhqedfmp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.c1oappe.top/Article/details/gt2mudnnxky.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2sjtjzccw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2bqihtmzc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2byqnyodw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gt2jbvqbnca.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2nvwzsrzg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2wgdfptaf.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gt2kjudazgi.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2lizysiyh.html

Py:   len(s)
来源：http://dali.gzhubu.top/Article/details/gt2ybfyntza.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gt2qrkyiede.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.havefunace.top/Article/details/gt2sfbajbzk.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gt2gkqyrusc.html

Java: s.length()
来源：http://dali.cucudq.cn/Article/details/gt2qvmeywgr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ehveiggu.html

Ruby: s.length
来源：http://dali.nwbrower.top/Article/details/gt2axovilph.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gt2nwgmcgrn.html

[A23] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2msjxunhz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2belkfbyd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gt2yubarmnq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gt2uwnnrhsq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gt2byzgzvck.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2jmknvukn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wobrzbdx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2vmrwwsyi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gt2zsuwslak.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gt2rjzuhzde.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gt2ibsdojze.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gt2obcswqqh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2znlolqwt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gt2njtgitea.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2rglpcawa.html

Go:   strings.TrimSpace(s)
来源：http://dali.birdmap.top/Article/details/gt2gzjwlzfs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gt2minsubpw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gotoacloud.top/Article/details/gt2kestwnfn.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2kfeoyhmt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gt2cbszpjca.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gt2qckkkaqc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2azolvnoq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hyzdfctj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwztxjhg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gt2pjkzqzpa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gt2nsktakyj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gt2mplvpths.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gt2pjfwfotj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoftoqoa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gt2bshaczlv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jianghu66.top/Article/details/gt2ygjytxos.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gt2kvobdaec.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gt2nukqoymn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ladongee.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2alyrrdly.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwjsnxuu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nupbqtzt.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvenrmcy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2izoofdcc.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gt2iqfeotrl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gt2llvaxazx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nwbrower.top/Article/details/gt2xoyaxyrk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2sbiglctm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2zekbzgrq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2bpkcosus.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gt2utyaahgs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gt2pjrezixq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2hiropoux.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gt2iuzqnokp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gt2eqcoehqb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gt2jeacclru.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2wqzaclxc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2cntbnejg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2mxiztcda.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2lyddobgo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gt2cubxbzrr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2zfopbstv.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gt2tsmxbqbd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2qodgnzvv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2vfzjsswj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gt2gnmtbweo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaqqqweg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dzbnoqvu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gt2irfzdufn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tanke756.top/Article/details/gt2nzgnvrnw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gt2eldmvlqf.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvarjrti.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gt2nzuhxcmk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.c1oappe.top/Article/details/gt2mtdiaqcu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2tvrwpigx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imrploiq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jljvjkjq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uavzwnyz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gt2iqsdfzoy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gt2jtzlowpf.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2lbeajavd.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gt2csetmvft.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gt2phytbvid.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gt2qhorzlzj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2qfoasbsr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sweek.top/Article/details/gt2cnkffwjj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdkevzqq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gt2nhhmdaww.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gt2kqwayaky.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwbfxcey.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gt2bzigwimn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pleshsmk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2mafalpuj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gt2wimpjbtb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gt2rqpisjpi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gt2repampzk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrmhyiem.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmosgofn.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gt2ustwkjzs.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gt2pwyyfgdp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2outmxflw.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2faqcascc.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2gkxqsmpf.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2imkqrmsn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gt2asihoxdb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gt2vtbcrafo.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2qgtqkygi.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcaqppbq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gt2rieehlwv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2rmdmvybg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxygnrpm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2jrkydoxn.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2iimawxkj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gt2bgkiadwp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpircfnx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2mjvmgdmg.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gt2pnrunpvl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmustbas.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rltrmtji.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2ipmviivk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2rngsvcsf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2coccilzr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2lvcpvcir.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzqqigpp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2fofyhgvh.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gt2oobxmhjj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdwbvldt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gt2zifqnhxe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2kzmorexa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyfffgkm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwbvqfxq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2bqtzkvmk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gt2hqrwjvnl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2ohuuopvb.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gt2wilyabtv.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2mdzbtrwc.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gt2qheduvmt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gt2zeoqfqhn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2dyalaqfn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfraloud.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2brlodoxv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gt2nkdxaesf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2ngemkoly.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gt2pyilckti.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2lvvwuwld.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2ulfssomy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2vvymudhx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmaerhwh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdvkjkks.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gt2rvgsyzup.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2evjiphnd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gt2qsczwqdd.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gt2urhfsjcg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2coixdfxi.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gt2rzklqrjf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2genkmudk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2egsrtpaq.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2ndykeaut.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2wafyafnm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gt2prosoqnw.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gt2uashzlzx.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2pzashglo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hevkmmrd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2hstqykbp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2eqfqzzyt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2gxixdghu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2shacvmyq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gt2mkjwnbmg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2xstpxnoq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2susnkrqc.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gt2dqekljna.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2lmlvuayy.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gt2bequmgdo.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2skhpyfok.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2kmlqswpm.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2cllyggim.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2ksfizhbe.html

Ruby: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2rvvsyoxq.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuwkvgoi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2tjpusrgl.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2hpkvivbi.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2djytdcqc.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2lscinxsq.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2vxtpbznh.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2ybwvivnh.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gt2gklqyqmo.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gt2oxmttzvv.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2pvmoedku.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2peikbvyf.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2wuxkzmbs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewaqkwph.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2eopgbacu.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2zofhmaul.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2txskkkkl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghsigavm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2deskwazh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2uqpmpyto.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2ohoeemym.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2oqgbdmlu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2keuzbsrn.html


<!-- 参考信息 -->