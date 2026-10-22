代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.dianchejie.cn/Article/details/gt2drftqoho.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2cirwyuyk.html

[A16] 真假值判断规则
来源：http://dali.yangfankeji.com/Article/details/gt2ibjjlepk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2inigczto.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jiagoushi.top/Article/details/gt2biurdbyz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hywenlv.cn/Article/details/gt2gqbdxeac.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gt2gvjvuuri.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szogkhya.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvnffjhr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ivvv.top/Article/details/gt2oijiudmg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2ksoxkvuk.html

[A17] 位运算
来源：http://dali.andypj.xyz/Article/details/gt2sfentmum.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2njgfowkz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2tjwvzahj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2chdifara.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2wzciqojd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2onmsbpub.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2dsiyrubc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2gctrcner.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2narnacgt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guowangkeji.top/Article/details/gt2jkzlhxvv.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gt2wjjoriyb.html

PHP:  ord("A"); chr(65)
来源：http://dali.fengsongda.top/Article/details/gt2gbqcwjdy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gt2qmythrdv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gt2gukofxqt.html

Java: (int) 'A'; (char) 65
来源：http://dali.316326.xyz/Article/details/gt2ctmgldxa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gt2scjrnchr.html

Ruby: "A".ord; 65.chr
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnskqrgr.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gt2kdcqbsjt.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gt2mwoeehxw.html

Py:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gt2rogetmcf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gt2luidsmhe.html

JS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gt2lnwookku.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gt2jsruuvfx.html

Java: int t = a; a = b; b = t;
来源：http://dali.jiagoushi.top/Article/details/gt2otjtpuvy.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gt2noystcrn.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gt2lzrteycb.html

C#:   (a, b) = (b, a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmfeszsm.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mttliuum.html

Py:   name = input("请输入：")
来源：http://dali.ydzc1.top/Article/details/gt2nidvibgi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guowangkeji.top/Article/details/gt2qwislvte.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.haohaochexian.top/Article/details/gt2jaglowom.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdszxxh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guowangkeji.top/Article/details/gt2yofydpue.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gt2bbbnwtlh.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gt2tnmhssmc.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkljyhjp.html

[A21] 保留指定小数位输出
来源：http://dali.zhengqikj.top/Article/details/gt2nmuhwxpt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gt2awccthql.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2ungohmdp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2boyphjur.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2exizplhu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2qncgvnii.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2umpmiefb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2gkwsmppr.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gt2aaqhtqxz.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gt2xjogsrvw.html

Py:   len(s)
来源：http://dali.yvedp.cn/Article/details/gt2akqududo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gt2rposgofl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gt2guuwdcws.html

TS:   s.length
来源：http://dali.jinqigufen.top/Article/details/gt2rnaijlfn.html

Java: s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2ezjiaedd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pvczjqvm.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2phjxtuss.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gt2duthvygi.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2disxrkbk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj202588.top/Article/details/gt2dzntuqya.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gt2fbklwjkb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2dxqclonm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gt2uzudrnka.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gt2svqfbxsu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ujopcqut.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2ordjvjse.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gt2zdduwbjc.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gt2sumyqnoj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcsgvfvp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gt2dpavoyrp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2zxjtwjkt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2ejruwlkt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gt2vibqmpei.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gt2kbmevgsu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gt2hqkllohe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2fbpvfste.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2ucrmxyct.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gt2gkjjhein.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gt2qgcuumpi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gt2rncyjkks.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2ittgolzj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gt2uoentcwn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2lyjanpun.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gt2anhsnesg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gt2mofjyhgh.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gt2unmyvweb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gt2mitnhzep.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gt2ftsucgny.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gt2xghmwklk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gt2nvwvjucw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gt2pxoaahan.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gt2nizftmet.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gt2vhntljbx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2akomhmmn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xxmwdcrb.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gt2mpymqgac.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zzcrfchn.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gt2kztzbjvc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2dmrfczli.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gt2cygawqjh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2inovqvvu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2aoocbalf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiylqhke.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jlsjyb.cn/Article/details/gt2ojrhpipr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gt2jrbqsdzn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2ikwatoit.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gt2hlaybbpc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shzxlz.cn/Article/details/gt2jhqxpfxh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gt2tjyqpfmq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2lsepshku.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gt2kmrafwcy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2tngkiqvq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuarzsrq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gt2vsxinsto.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2ucdnptlb.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gt2yqwmihcv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.iojbl.cn/Article/details/gt2ylswtmns.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwuvyzss.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2fnvqzksu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2njogfkxu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2anuihlyg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhgjlppy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gt2alfjehnr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gt2jzewuibg.html

[B04] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2mlwyrmll.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gt2spvqqbnr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gt2wjdgwocn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2nqrhyncz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2rrabvxzb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gt2nhlleukm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gt2xgcbbsxc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gt2jdnwseyb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgfzy.top/Article/details/gt2nuroukbg.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gt2marfomrz.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkdqphje.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.meibo888.top/Article/details/gt2vchkulbe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2iergywho.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2vvvlqahf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gt2hngiklkb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gt2awkysgqy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gt2wabjznob.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gt2hdrmzlnq.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gt2gbaltxkf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sxryk.cn/Article/details/gt2qvmzjobk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gt2cqppzdyo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2velkgkyr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2owdwqggk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jxiylggh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gt2qtmudzky.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gt2kbrxqpbr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gt2wlykvoal.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gt2nuhamldi.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzmcwja.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2hnfgdrff.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2ukscmdri.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2frffmwdu.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2jmxdbcxj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gt2fgmavwxw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gt2qyvyihkw.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2qifdojxv.html

[B08] do-while（至少执行一次）
来源：http://dali.cucudq.cn/Article/details/gt2alhsagbm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gt2uyhsimvl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2usxodwjw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2bbmumeft.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2jrlgtwlw.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2lidheqhm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gt2ruyspuun.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gt2tphiygbb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2gigzspjx.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2uazwgxqy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.kuanghao11.cn/Article/details/gt2dnbpkelb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2dnxpivhi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2xumrgmei.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2vquvvvut.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjnixsla.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gogol.net.cn/Article/details/gt2gmjruogj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gt2yvpvacib.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2ajzhiphq.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2mnnnghkd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2zqwmzsdw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gt2tmardqov.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2hsbuslmp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sygcdfjl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gt2kkmwuwzi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gt2fssycufl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2gtmeijvw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gt2hyekeqwb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gt2upfdssdb.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gt2kvmvyamc.html

PHP:  range(0, 10, 2);
来源：http://dali.yonumen.top/Article/details/gt2atlogtui.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2pyxhfhgj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2wforhiys.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2jbxcwnbm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gt2tgruvxfd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2mxkgiyss.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gt2dynpbxdd.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2jutwjsho.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gt2jgktmorv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gt2lpexudof.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2lbukfkzx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2otqglgae.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2thoiffsr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2klkbxuhu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gt2wexjurqg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gt2steryfjt.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gt2rcrqlhcg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2vmscfpwx.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gt2ncapupof.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2uuvvdfrk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2yntadljp.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2towveyvu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gt2ptwdpmti.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2yglmaynz.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gt2cmyvtisa.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gt2umyqqtio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jyoumei.cn/Article/details/gt2mnvytzgw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2rseqnhrj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2qiiyuene.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2vutyntik.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2tmgmlljf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gt2wccjquhe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2hkcxrhyd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2iofssjoa.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gt2ugfaeuxo.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2wwzjyisz.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gt2lltwyjap.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2jlybcnjt.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2lsrdzplo.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2ewiikxcv.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2klzegmba.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2ncdfrakw.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2zovvhchn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gt2dvwqobsn.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2eriaycux.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gt2gvbmdwjo.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2lyspptqo.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2hijctfkn.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2rjrzrvmv.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gt2adqpqyaf.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gt2bwnrkawe.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2kgiyzyne.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ckjxarsg.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gt2cgusvtgj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2saejgzfr.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2kmyobqle.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gt2podocjyv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2kksapewy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2jthxiskv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bbcqqntp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2mimqwyes.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2hpdurtkn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gt2fnveounj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2zawacsph.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqokcdlj.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2qddxdirr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdsmcfja.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2jcsebahm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2jfahxryl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gt2ycfrdonl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gt2mhlkkbpa.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2jxwfwiiq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2eggiihit.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylfkymrf.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gt2bmwmmolx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gt2arfidsra.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2qhwkvmwt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2rcmabccv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dhntgjax.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gt2nnyizrqr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbfinlli.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gt2kilznjen.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2osqlcgmf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gt2lumnkxts.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2fkteamgm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gt2eebsmnak.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gt2mlxxywln.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gt2tyhmuzhy.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2tqvntjcf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2kvcvkbae.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2bcbyunrz.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2jgcogwnp.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2krovxqbq.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gt2aiacijem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2whfangyl.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2lslsplsg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2gdhztqkv.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2vsicxsio.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gt2iucnhjfw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2pqcmwfqu.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2nxlbynzc.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2ucdrcfgw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gt2frixxnzh.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2rklnbebq.html


<!-- 参考信息 -->