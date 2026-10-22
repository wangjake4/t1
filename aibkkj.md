代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gaohongyu789.top/Article/details/gtgphwyhvs.html

Ruby: "Hello, #{name}!"
来源：http://dali.xinyue.icu/Article/details/gtujgmmrta.html

C#:   $"Hello, {name}!"
来源：http://dali.gzhubu.top/Article/details/gtxgeaollh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhoulong.xyz/Article/details/gtzbxiyhzd.html

Py:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtivrdibgw.html

PHP:  "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtvhdrvdbl.html

JS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtfmmhsznb.html

TS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtabmvlqlw.html

Java: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtzbcdpjcr.html

Go:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtwplseldw.html

Ruby: "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtkkughkmp.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtrfdjtybm.html

[A14] 注释写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzruajfqc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenzaomai.com/Article/details/gtusjspidc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvvdqrai.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtdcajarqi.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtddnrzdnm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.kuanghao11.cn/Article/details/gtgapmksea.html

Go:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtnxszotub.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gtszqupfjq.html

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtrgenpghd.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnsyuhcv.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtuuqwtgnh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtulrkqref.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtnassmarp.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtsmmkwxds.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tanke756.top/Article/details/gtsrkkymiz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ppjwa.cn/Article/details/gtzlupwpgh.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gthpycefjo.html

C#:   var value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtrlymhddj.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gtrourhbrv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yonumen.top/Article/details/gtjerzmoln.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hfpthk.cn/Article/details/gtohxzdizb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtspuhcozd.html

TS:   if (!x) {}
来源：http://dali.xinyue.icu/Article/details/gtzrqozlbr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aibaodan.cn/Article/details/gtgufioelw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtcenpjuxd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gtjvwxcwek.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zycfv.cn/Article/details/gtgbruwnla.html

[A17] 位运算
来源：http://dali.zhongyouzk.top/Article/details/gttrtkqxty.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtmrekafxs.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pycfn.com/Article/details/gtegdmxeuw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtrnndcdpm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtblaquhxr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtllatvjig.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtbqmmqjva.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtxxfqsmiu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtntwljseo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yueranfly.top/Article/details/gtcymagzbm.html

Py:   ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gthgufstdt.html

PHP:  ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gtmehttemz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gtjdfigzhz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtrnmyostp.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gtvgpoewsj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xylfe.cn/Article/details/gtjmdwawgi.html

Ruby: "A".ord; 65.chr
来源：http://dali.sxryk.cn/Article/details/gtufaypiaz.html

C#:   (int)'A'; (char)65
来源：http://dali.hywenlv.cn/Article/details/gtgaaxettl.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafcmomyb.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtneytnlhf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gtuakixbrt.html

JS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtrakisvqi.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gtdqcnkscv.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtuvhsuaho.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtqebojrlm.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtfxlsiroz.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtojatfweo.html

[A20] 读取标准输入
来源：http://dali.vqdsnc.cn/Article/details/gtufptupqn.html

Py:   name = input("请输入：")
来源：http://dali.jlsjyb.cn/Article/details/gtgknvpgpn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258888.top/Article/details/gthnasatbg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.redwolf501.top/Article/details/gtxhjlwjrk.html

TS:   // Node.js：readline 模块
来源：http://dali.ivvv.top/Article/details/gtwqxsgwgj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cheryme.top/Article/details/gtphwsswto.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gtrmebsrxr.html

Ruby: gets.chomp
来源：http://dali.ybcxt.top/Article/details/gtxpglgnof.html

C#:   Console.ReadLine();
来源：http://dali.ehwqpu.com/Article/details/gtpqgdmovq.html

[A21] 保留指定小数位输出
来源：http://dali.nwbrower.top/Article/details/gtuvrlkipz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gtbzbgptcn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtudyjarhw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtfuysezga.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtbzxesxce.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtjtgzwnne.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtxxzssqli.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtelqmjmif.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gtorrmamnd.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtshbmdfvm.html

Py:   len(s)
来源：http://dali.gzhubu.top/Article/details/gtomodszyj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gtjprvhotb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtseoztubn.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gtezsmedqg.html

Java: s.length()
来源：http://dali.tian-w.cn/Article/details/gtkluskxft.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfypjwbzl.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gtazikdswj.html

C#:   s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqwvxauz.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gttckjxcww.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jqgfzy.top/Article/details/gtgbwulwky.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fengsongda.top/Article/details/gtyvgmxaga.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtiwuetsnl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtclzhosyh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtapsgrxib.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.9152youxi.cn/Article/details/gtnqhxovrn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtwfiamjll.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gttuojjzbj.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtuhcvbsac.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gthfxdoaoa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gtuliuogpc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtoadnnsyw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtkhvnedfk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gteobjdmew.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtvwxlizah.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj202588.top/Article/details/gtxlexnvdv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.birdmap.top/Article/details/gtuscwgcru.html

[A25] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtyynkinht.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyotrnjie.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cqqwz.cn/Article/details/gtppzlszbk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nwbrower.top/Article/details/gtzqgcsiki.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtduvyyzvx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ppjwa.cn/Article/details/gtyhazqjzy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtuvnujjir.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gtphatoqfu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtguzidvlm.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluakjhfl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gtptpvfrmd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gtqhqkmaam.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jiagoushi.top/Article/details/gtcsilopgr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jiagoushi.top/Article/details/gtxxkfmvwe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yongpay.top/Article/details/gtmgwwfwxe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtdbahtjma.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gtfyiyuarm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtltbxslku.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpmppdjyv.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gtnovhbfbh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdclpfnyo.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtfuoyqyul.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gtkdkvrpxe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nwbrower.top/Article/details/gtqlivrhwp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtyaowksmc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtlxmqjhjv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtrvkwowdc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gtazdqihdw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jianghu66.top/Article/details/gtqkrkcdxj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtuniavrbh.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtvlpgqhvv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gtydwbhhxr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gtdgkflwhf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtzqwlkcmm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtjgtwdcez.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtzoewnagw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtombvoiya.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxolzrkh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtsvxyeciy.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gtboekrhdy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtvocmbypp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtxwdyghan.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtppzhvxeb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtriayuxvi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtijolsvis.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gtvdycsrlp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.birdmap.top/Article/details/gtajjwrsug.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtdclzsurt.html

[B04] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtnmhtrzvd.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gtrbxlpgky.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gtgvtfoaan.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtbhnyupqs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeinzlzp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gtlshrqvgr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtsvdomtki.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gtpsfyobfi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtshffmbkl.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtaaybzrmb.html

Py:   for item in arr: print(item)
来源：http://dali.ehwqpu.com/Article/details/gtxecgmvjs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtesmxstfh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtsoiixzht.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtxmzbrigd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtkvtduhde.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtbkfjrrgt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gthqsafstf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gtcgsgupvx.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gtwevpwwfd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gtriiomfnb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gtrbfqudno.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtrmlgdccj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtgnxxgvyf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtnwveluzq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtonmhrjmy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwulncrbo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdropxys.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gttdpleufh.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gtmxpeinnt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtqjcjegig.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gteivkwsrz.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmbzqzhdo.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtnfmxbczl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtyyrdrofe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gtxkayfxse.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtimajddtt.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtzbkxbnbg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenzaomai.com/Article/details/gtqozuimyo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gthqcjchzi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtkusqieqt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtrndappwd.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtmsgusuix.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtgdxzigbf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gtmznqnwqp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gttizvwpbc.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtdwhrrxdz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gtaehhrxkl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtwuliunry.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtlmlsegxs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtmbnmnuuv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gthttncxbg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtmquywxxm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtcbisslhm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtixszboxn.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtwomyvgtz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gthqohxrwz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtqjoutpct.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseqqllud.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtuxsfnxec.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gtzjbeoylq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtpxnpjzzq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtqccpgwrd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtxqrakoox.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gtlocayzui.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gttechtrnh.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtikcpcvvz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtgwbfpesx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtwnfjpbtd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtfzsurdjc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtxqkkrsxz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtpsfapubj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gtdflmgggn.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gtjgkxxefx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtxvqmnpge.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gtdhzohyeh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtofdmlgfe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtzeuhrpog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtlipygltx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gtatpldlxb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gtzvxkxfbo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtsdjgckno.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquezrncb.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtzotnpbnc.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtjoknnysz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiicsvyxl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gthokvojnk.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtedtohkzw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtsmwmcfsw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtoiuyiipm.html

C#:   x is int or double or decimal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqpnetcz.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gthywkqzab.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtnhpyfhjg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtnlnisyac.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtpcohnyml.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtxsctvlzi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtlggkrnqw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gteosifgjf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtagcgovsb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtjupvektk.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtubzdceed.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtxwihqzvq.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gtfvcaathz.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtuhynflcc.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtrwdjsosu.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtzulrczru.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gthnshsgxb.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtjapickoa.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gturamyhxf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtbocejpif.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtzsmfsmda.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtdznntptp.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtcgfzvcnj.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtddtnnibi.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtykneyfpp.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtxzxnwvuq.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtpmgnzsvn.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtzztcumor.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpgomwkpe.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtpxlxtcup.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtllvkmmlc.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtrxgrauyw.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtfadahuys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtybngseft.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtkqyaslxn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtynvcoihr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoxrxrsr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtwufkvnxc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtcjxvezcq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtmyvmjfxw.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gttzsxcovi.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtpdiiiezf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpgvaurop.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtvovleiil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtakevflfq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtwhcnotuo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gthoosaswe.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtdwhxmszw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtyactgwin.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gttifikpwx.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtledbiwvn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtegtmjlgg.html


<!-- 参考信息 -->