代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuozsmjf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258.top/Article/details/gt2blgdwzhi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.bjfxy.top/Article/details/gt2rggycper.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gt2pqoqwmiy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2yknshjsa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2kzpybojd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2gwgranwt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qupbqrsp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2nvathvar.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2mlyadqpr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnmxsdsj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqtpzbkm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.quarkkingdee.top/Article/details/gt2guayknnf.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nucypswa.html

PHP:  ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvlarwzo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gt2kcofpmti.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gt2sxazrkba.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gt2tsdtybaf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gt2fidbhwzz.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gt2bzpkqkbj.html

C#:   (int)'A'; (char)65
来源：http://dali.svipenyu.cn/Article/details/gt2nkgluzol.html

[A19] 交换两个变量
来源：http://dali.havefunace.top/Article/details/gt2xpscxxel.html

Py:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gt2wwenhust.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenzaomai.com/Article/details/gt2oqxittxz.html

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gt2btjjneuc.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gt2bjungmkl.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gt2wpviqgld.html

Go:   a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gt2wewayhgx.html

Ruby: a, b = b, a
来源：http://dali.yonumen.top/Article/details/gt2ycukywsu.html

C#:   (a, b) = (b, a);
来源：http://dali.jianghu66.top/Article/details/gt2eeczqyhf.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gt2otenketj.html

Py:   name = input("请输入：")
来源：http://dali.jyoumei.cn/Article/details/gt2bosvjurb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gt2pbbtveoe.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gt2vgsmgqgr.html

TS:   // Node.js：readline 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2oexbjmvc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gt2lbtikfdi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258888.top/Article/details/gt2umkufmgh.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gt2evektezq.html

C#:   Console.ReadLine();
来源：http://dali.pycfn.com/Article/details/gt2yiiwzrud.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gt2hcxvxpby.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gt2wvnyyced.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gt2utcvnrnm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2ygdhrruy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2vveznpdv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dynkzezw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfqejazr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2anyqhyjb.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slceqyfe.html

[A22] 获取字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2kqxqnmcn.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uajandul.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yanxiufei.cn/Article/details/gt2gxtgrlal.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqvrpmnc.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gt2tpfswhjx.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gt2kvtchslu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2hbbhnind.html

Ruby: s.length
来源：http://dali.aibaodan.cn/Article/details/gt2uwxjbwzd.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2wjvjavmc.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2smtdbsyw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuxming.cn/Article/details/gt2buwrflrh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gt2ehgdohnz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gt2obuauzzf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2vhmsadfd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gt2amchzbec.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gt2lodcqqwa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2cdxxtmbt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgufenzy.top/Article/details/gt2eanxwvow.html

[A24] 去除首尾空白
来源：http://dali.sxryk.cn/Article/details/gt2gsvjeukx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gt2vsvsqgmk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gt2gbeizjtd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2balksvuv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gt2vvfkvvyk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.c1oappe.top/Article/details/gt2vmpotfnh.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gt2twkuaone.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gt2qqvedmob.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuanzx.com/Article/details/gt2sfqkyktk.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2spuajehx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gt2lmhywuyl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gt2ohipdyyw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lppdamnx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2iuvuzfea.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2vtlculeh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gt2jimzweub.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenjidiqi.icu/Article/details/gt2stxmyral.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gt2yhkykxvs.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gt2iogcqolb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gt2foupbxcl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gt2yzfvncyv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gt2mwikfcei.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cashguo.top/Article/details/gt2mvporqsa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gt2ufxdxknx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gt2euhpywmk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gt2wgmqurig.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2aphafugz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gsiwbrkq.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gt2snkwntwz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2isbgsqlv.html

[B01] 条件判断 if / else
来源：http://dali.jinqigufen.top/Article/details/gt2gbwrpyag.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigufen.top/Article/details/gt2ncjheuhc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2vvfbluux.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2kqxyrhhr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2oedkkinv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2tvnaczjp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cdnleiting.top/Article/details/gt2dquhuggz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gt2lpxepebg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxdovasu.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gt2fxbfezko.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gt2nwdpsiwa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gt2noopcngf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gt2gjroruyz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2wfwaioxb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2ceuaeahe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xziqi.cn/Article/details/gt2rofnkjxf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2jptifsmf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2lmdarnjf.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwqknkpp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gt2sktyvvim.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2hqlvjren.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bitclyoj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tzfodbvx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2kcozdajb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gt2ziotnqet.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gt2fppxmxzc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2tqxjrsmd.html

[B04] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2thpfgmko.html

Py:   for i in range(10): print(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxfviyab.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gt2oaikmyxo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2udskbhkj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gt2owhcjjvd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gt2bgpswcwy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gt2zbxtfpic.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gt2zrhvjcxi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2tljoidon.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2ufdlttov.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gt2oimcqgct.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gt2eqgjbkqt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gt2bdtkdcdi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gt2vezzjbcd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gt2olsebjdc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzhqtigh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gt2mdficcsw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gt2rpdqsobc.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gt2tcjgoyeo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gt2tkjfagar.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gt2caaufvkf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2grpkcbyi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2mdycctmo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gt2ygcoeyab.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dovfwmcc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gt2eztmrtql.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2fwublztw.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxuyvlzy.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gt2ngnzjnkd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2rmtgymgx.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2coqtdhge.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2xbsrkmkf.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2idyqpaaz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdippnmk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptgzglnm.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pckpneii.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gt2vnacqxak.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gt2eobbmszv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2ouhyopns.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2woqyuxea.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2zpmxsrwr.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2softttfn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gt2azwfavkc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gt2hgiztwwm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2vtdtfhet.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gt2nepmdmkx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2phjvpuls.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2lubnkuch.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mznrzbpz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2jrdzitgc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwcjtrtb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2ugzifqjq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgufenzy.top/Article/details/gt2eultakqa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2nkiljboi.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gt2ejwbqkhi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gt2njomazqg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gt2oxipdjat.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2ituxoqsv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2mrrrntzr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gt2anjusadn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gt2nyjtczik.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gt2eqoljkyp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2mfpdhqsc.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gt2mthfvtba.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqposbep.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gt2hjsrplia.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2aguekddn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2wwkbizcr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2nbgqfipf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gt2fexsnilk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lninlcsw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gt2jvwlgxpu.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gt2sihvcxyk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gt2lqsisksd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2yiowhloj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ntbgrrhv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2dslcclze.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2nagraveh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gt2sbrsrltg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gt2iydaapdv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gt2znvnzrfb.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gt2tpdqkgig.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gt2ecyjhnyh.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwpjclnb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2lmstwlnt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2gaxbcmpt.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2qirpkxyl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gt2yuzpztti.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2dqvafqqf.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gt2qaushzdl.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gt2grdxdycl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gt2eassbqvi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gt2ezpfdpjp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2glqpnmcd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2radevpwj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2ttbjaisw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gt2xwkyqycp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2gnbslaep.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipbkyxrd.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2gjzmffat.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gt2jvzedcfq.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gt2mwuspjvw.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2woohanad.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekzqgpuv.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2lozvthal.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2mtqiahtz.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2pplbhkqh.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2taikwilc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gt2mlpxglvf.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2hsyrhyyd.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gt2plyjmwsa.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2mtzwyslp.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2kymfnlmb.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2cxssxxnu.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gt2wkxuwnti.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gt2qkfdxgot.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2vkvdeicq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2frqvdegd.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2ioypsslz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dhffngke.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gt2kkuujuvj.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2otbbgifi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2uyfkrbnn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2pjwynmuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2hdqfance.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ztqapasr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gt2wopsovni.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2vegvtask.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2ajegqiac.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2byftmyed.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqvexnnz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gt2caghrlel.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2sjsbxgid.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2mreliwqz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gt2fibsstpg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auxepwik.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gt2wllksers.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gt2amgyplln.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipwtxtby.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gt2sizglytp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2seuqrmzh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2lfpeuktu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gt2yhrrgjzp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijszsgwr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gt2zfigcmvd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gt2cqtscrou.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2etmnygzh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gt2ahjllhho.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctuhseya.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gt2mulliksh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikckttpq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gt2homrppby.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gt2wqcdbnms.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gt2unkwoszv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2ieuexigs.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2tzadsxrq.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gt2glveskli.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2hucfbyao.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gt2cuceiuai.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2oqixeymv.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2dwyjdepi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gt2pxryonzn.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gt2ahosfhtt.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gt2adkokorn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2gonafowh.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gt2vbxxfeol.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2dsesydfp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gt2hahxkjzl.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2efuuyfvl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2wkiojhdv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2xtylvlww.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txgmywxk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2hmaydafm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2jrheojhw.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gt2rmrkbvvf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gt2klywknqj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjrxbywz.html


<!-- 参考信息 -->