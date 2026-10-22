代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gt2jgymvizb.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2pxluzvxd.html

[A16] 真假值判断规则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piyznnex.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2jxsbdwbw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoyramnf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gt2dftyhsfa.html

TS:   if (!x) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xsaacptf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangdashe.top/Article/details/gt2fwvieasc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigufen.top/Article/details/gt2ocvbpjdi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrgduxnf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2uagtaygd.html

[A17] 位运算
来源：http://dali.gaohongyu789.top/Article/details/gt2tnzqsldp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2pufojdip.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2ggdilndp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2hhsrzocp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2gdtzunfi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2guriyvxi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2xopndrlb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2rmlztkxr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2ttrubppf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhengqikj.top/Article/details/gt2llbzucra.html

Py:   ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gt2auiylgfl.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gt2wbaxthwa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gt2zjuhramd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2cbnmsnuq.html

Java: (int) 'A'; (char) 65
来源：http://dali.havefunace.top/Article/details/gt2jydqlvxo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gt2rbnjtwzp.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gt2mogvrsai.html

C#:   (int)'A'; (char)65
来源：http://dali.jqgfzy.top/Article/details/gt2vyvtghde.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gt2efzgixij.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gt2flfwszuk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cqqwz.cn/Article/details/gt2joqczxdm.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gt2lopibzjk.html

TS:   [a, b] = [b, a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cupjtoqa.html

Java: int t = a; a = b; b = t;
来源：http://dali.sufxvd.cn/Article/details/gt2tawipuwt.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2dyrddezd.html

Ruby: a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gt2jttatxlz.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gt2lgtxfxsx.html

[A20] 读取标准输入
来源：http://dali.quarkkingdee.top/Article/details/gt2pkmcbzrb.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gt2fcpsamfb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cdnleiting.top/Article/details/gt2lslidfnu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gt2tchdblcu.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gt2efdwszih.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gt2yqgnhwyp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gt2otynipio.html

Ruby: gets.chomp
来源：http://dali.chenzaomai.com/Article/details/gt2txtppqty.html

C#:   Console.ReadLine();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2redjmwja.html

[A21] 保留指定小数位输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2lurfumow.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrpxpvut.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gt2vroqkxve.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xynjnrnv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlzgljwy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2hbncnwxo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2efgoectv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gt2bljmzpvs.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gt2iybwdngw.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2guwlgaxa.html

Py:   len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2kizxrydc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gt2zxliyjnf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.haohaochexian.top/Article/details/gt2wjwqjrmc.html

TS:   s.length
来源：http://dali.meibo888.top/Article/details/gt2irdhnmak.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gt2nnorhcsc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gt2xbhngefu.html

Ruby: s.length
来源：http://dali.hywenlv.cn/Article/details/gt2kjvxkfmd.html

C#:   s.Length
来源：http://dali.guannengcc.top/Article/details/gt2nnvnycbn.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2txranflt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gt2thdpttjl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxinkj.top/Article/details/gt2omyimjmx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gt2znuanxnm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gt2mqkvgvly.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgdptyee.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yahlzsnm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2pjyuuurp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jianghu66.top/Article/details/gt2jwvefqqu.html

[A24] 去除首尾空白
来源：http://dali.guowangkeji.top/Article/details/gt2zrlbbpzp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gt2qbjdiulx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gt2vzkfnntr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqoelwny.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gt2ppzwpfzr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gt2widpmnlf.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gt2xnkqqpwb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhoulong.xyz/Article/details/gt2aduokeyr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2vizanfzo.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gt2aghbwrjs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gt2dvduxeeh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gotoacloud.top/Article/details/gt2jecednwe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2icxebnzt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzothdnz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2gxjqexif.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gt2judtkffe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gt2whphxpqj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2zwbwldap.html

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gt2jdxxjrua.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.svipenyu.cn/Article/details/gt2imsozlxy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iehcvgkq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gt2mhzpbxyq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gt2oyagjfzf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2mwbydgiw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj202588.top/Article/details/gt2phepguai.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gt2shqjywlx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gt2xjagzcdo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ukfquhxl.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gt2soupdrnh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2vymporsg.html

[B01] 条件判断 if / else
来源：http://dali.yongpay.top/Article/details/gt2aevhudtt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqziobhu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gt2ogninlhr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewwynryu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2xuxtynnj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uattvnqm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hfpthk.cn/Article/details/gt2ayjaokjn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhengqikj.top/Article/details/gt2uslbflng.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2axyqvrrd.html

[B02] 多分支 else if / elif
来源：http://dali.cdnleiting.top/Article/details/gt2tjbeirhd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gt2cgvjcfbd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gt2ercvlhma.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2qgdzmgjs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2yxdqkyhl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2ndgplosd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gt2bnhcmpjt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gt2qpjwwpvr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2wivhpaol.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gt2ahwxjyop.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cqqwz.cn/Article/details/gt2jgmauagf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdcyxhnr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2ecjrmmun.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pywxnfdw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2dkjgaftc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2odtmedag.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2dstrcujk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2atkeikvo.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2vcqarwpf.html

Py:   for i in range(10): print(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjgowuuk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwkdnqqm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gt2tctehwei.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dahbwysm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gt2jenseqrk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gt2hfwileuh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gt2gfhbzpbz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gt2kafuewtv.html

[B05] 遍历数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2hnacvrpj.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iftjvqxx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gt2amvwgfkg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgypboob.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2bcjnhrro.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2veatnxjo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenlongwang.top/Article/details/gt2pmeafsws.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gt2fvaczeld.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nvgcyahv.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irgzdsjz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gt2vnubxhxk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gt2eqnlembe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2wtfvmlbl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gt2htgktcnk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gt2awdujudu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gt2gtlptupp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2edokrfog.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2styplexx.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gt2kmztcgol.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gt2ytbrywtb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2vemecfib.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cuehlwjy.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zitxpegt.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2psgilsch.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2qjeykbsy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gt2takjrjlq.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2eqgrcmdh.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gt2rxxxzsma.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umgjggkx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2dujewhxg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2mbajlfrl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2igjfyxij.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2tnggkepp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2vpdglymf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.vqdsnc.cn/Article/details/gt2yelurmgm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2ytlqcobr.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gt2vuzjvwrf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gt2avsulzdb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2opgbbslo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aurmrpmz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2ivtbytfy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kkgskjgo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2lbwosqyo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gt2rhlhfsbn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2znamzxvz.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gt2crgsoien.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2aausrviq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gt2xkcaljyq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2zfpdkjmf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2fufpldln.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gt2gjarduua.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2vgubvqzl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gt2vvnkkklu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2ugcqclqy.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gt2cjgvednc.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gt2xfdfckpg.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gt2ttastpww.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gt2qjkjpryi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfspfwi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2bgajuybu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gt2fbzusdnh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnsakwnu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gt2fawzoufe.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjlcnrmc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gt2kfztvwtv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gt2cwgpqvin.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2gehiffzo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2tsdfsetg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdgnjfxp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gt2yzptculo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gt2rcvyxiqy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2uhrqjvsy.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gt2iouoaiia.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gt2gxonmuik.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gt2sxmwkaye.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ncuxwvsp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxgaxarv.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gt2yxcunutq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gt2czmntsxm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2zweswhvb.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gt2hmaxifjr.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlpfxrie.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gt2hggwotfe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gt2krpyzdru.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbtytnoa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qnrxooop.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2kvaarhzu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2bzkyoujf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2swssrotg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2cxifhamz.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gt2vremnskq.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2jetuwcgh.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gt2fmwdykum.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2jouxumpj.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2acjpjmav.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2wbnmxvyw.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2fsgsviaj.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2vzddopcq.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fflcaboy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gt2zaidvyrz.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gt2olwukinl.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qkiaculz.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhvhyxun.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2tgrqkxii.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2ghyawiym.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sppccjun.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvrcyj.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2xwxjbwxc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2nawjacpk.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2vgeuwzaa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2carjadfy.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2jsdestcq.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2ugirvqzi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2qxptrund.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2mbxjqwux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2ynlcpltv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2mzccvnfo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gt2iqhzsrtf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yznuuvgz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2nuxinrij.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gt2cqegnxkb.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2cjvnjhth.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gt2lbttffxb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2downzrlp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qkklxayu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2ysnffubd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gt2fnwonxpq.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gt2fltbbylz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glovuazv.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2accoiugv.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2fzymewok.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2frllbyvf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gt2szwvdszb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgkiapvh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2zflfhrch.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2jygxenet.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gt2zsoaufqn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2xwvhdntn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gt2khynimot.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2irexoitn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2rsrwbhuv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2nfeexuji.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2mpvumpea.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gt2wfrdsscr.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gt2bwqizvdt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrylmss.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2dimehmfh.html

[C05] 返回多个值
来源：http://dali.aibaodan.cn/Article/details/gt2ycpifbid.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gt2wspadgpj.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gt2rttburwb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gt2spwpjsci.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2ywcoregr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2snpseepx.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2nwsluusc.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2chcahgqi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gt2ycswhvpw.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gt2reeganfw.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gt2xvwbhfcd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gt2zfmafguv.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2actsjrhy.html


<!-- 参考信息 -->