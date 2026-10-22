代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.chenlongwang.top/Article/details/gt2zhiuzccf.html

Py:   ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2evmegmkw.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gt2odqvcwxg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guzbyyqt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gt2zkiwqacm.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gt2uwoqtawo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenzaomai.com/Article/details/gt2stvaslbb.html

Ruby: "A".ord; 65.chr
来源：http://dali.gaohongyu789.top/Article/details/gt2wwljferv.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbdpobut.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gt2yvgagqdv.html

Py:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gt2qhpaiehj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.kuanghao11.cn/Article/details/gt2nxbxyzqr.html

JS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gt2guxlggyk.html

TS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2ogntrgtd.html

Java: int t = a; a = b; b = t;
来源：http://dali.guowangkeji.top/Article/details/gt2yvsjijwq.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfqirjbm.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gt2fzqnvvbx.html

C#:   (a, b) = (b, a);
来源：http://dali.dianchejie.cn/Article/details/gt2fitjyaps.html

[A20] 读取标准输入
来源：http://dali.cashguo.top/Article/details/gt2ckgbhcfd.html

Py:   name = input("请输入：")
来源：http://dali.cucudq.cn/Article/details/gt2bbzjtazb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhldycco.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hammf.cn/Article/details/gt2zklqdxvp.html

TS:   // Node.js：readline 模块
来源：http://dali.chenzaomai.com/Article/details/gt2zbptwmgt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gt2xhkcafrd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzxqvusd.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gt2bziahzbh.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gt2pvglsimc.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258888.top/Article/details/gt2yhinxwcp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gt2ubkygwte.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gt2zcopxadq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2ulbucegk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwoheqfk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2nqubcdww.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2fwhnklpr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2syquftez.html

C#:   3.14159.ToString("F2")
来源：http://dali.daxiang520.top/Article/details/gt2flhncejd.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2mrwpbvgq.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2azfddcac.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gt2aiogobac.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ivvv.top/Article/details/gt2yhvdeubm.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gt2drgigtse.html

Java: s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dryicgyz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gt2gicckkht.html

Ruby: s.length
来源：http://dali.pycfn.com/Article/details/gt2nnotpruy.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gt2fanngabf.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2eilmkdaa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2wmwtgljl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2uuweuotk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gt2lkiiwopn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gt2qulcmalx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2nlpaaxrn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgeswopb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gt2ftomtbbu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gt2ohkqoxeo.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gt2rhxfwcmc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258.top/Article/details/gt2tjbwiwzr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbmhqaqf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2lraqacft.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gt2nrtdaemt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hysaishi.cn/Article/details/gt2swekhpov.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgfzy.top/Article/details/gt2nmioannc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj202588.top/Article/details/gt2mpkpauhp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2wmkuhgmh.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2nbilruqv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gt2shbpmhvj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sweek.top/Article/details/gt2nppnmyao.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gt2oykujxrq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvfazyx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gt2ysznsjrm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gt2oikzlwxl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2madsmjja.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2hdfyoizk.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gt2ulbqxbcs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2wbowopxi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gt2oullzrwq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzsseqqy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.birdmap.top/Article/details/gt2oivuidon.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gt2twovyxjo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gt2ybmivlzu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gt2nmmirolx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gt2waaiznkk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jworsodf.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gt2eczuydoh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dghhhrks.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gt2uieuwicd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gt2cetrliet.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdnetmrv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2wfyxyoyz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcpxrsnx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvlylrxd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gt2agqpvddh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gt2ibpupiqp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2emjrsops.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gt2wzelyjfh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gt2lhubfigu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ppjwa.cn/Article/details/gt2yhtqqdxd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2fbgrwyuf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2rizmexis.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2kmcpzzdm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gt2vitswwcm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.andypj.xyz/Article/details/gt2hjjvznqz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2naiovmnj.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gt2glhsookb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gt2jdrzwxqe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xtspumom.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2usxrmldw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2owlbbpzu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2esvtltlu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2euqzoflc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gt2ipsrpbkw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gt2tldbufgg.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2fcqxghzx.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gt2jjetyvws.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gt2cctehcep.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2rrwnoczs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gt2yulowlch.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2twkxeemj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwvvncxp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenjidiqi.icu/Article/details/gt2olgpqnnl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gt2biapdckv.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2lhsgidop.html

Py:   for item in arr: print(item)
来源：http://dali.0kj1m.cn/Article/details/gt2yqzwbuat.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxwizwux.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bywtzxbz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2bontsmsr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gt2lnxkpfop.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcnevcnl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gt2ezyahayh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2kqyknrfg.html

[B06] 遍历字典 / 对象
来源：http://dali.yvedp.cn/Article/details/gt2ialaoqjt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gt2sdnqmtss.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rztzkcpn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2jkwkdcja.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2lqfcxdec.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gt2wkndemop.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gt2koeayoqt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmpszlxz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2gpkehrik.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gt2aayqoukz.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gt2zdivnepf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gt2yglxyqod.html

JS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2pawyrugo.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmrycgsy.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dhlkcatn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gt2hyycpxww.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gt2mvemspgt.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fylwmmyi.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gt2xtfcxrhn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gt2rkeqkspr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2mzjrkqcb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2wuyvryux.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2mochxifv.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2yxqzbkor.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhwvcbck.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gt2dgbarezp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2epolmzio.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlyerwam.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gt2uyxujzdh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2ontewraa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2clulttnm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2iakwrhtu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2bkspzecr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2xfempuaw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gt2tzmynbqu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2usnwkigc.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2croxmnej.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gt2adbobgtx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gt2mesxixqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2qehvyvgu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gt2jqzzlotq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gt2htecrogo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yvedp.cn/Article/details/gt2aygoktis.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2dlcvkygq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gt2lmtsvsht.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gt2dlqoadki.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gt2gavfqcyw.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gt2ycbwtcpa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2bsuskeuv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2lbnzstjn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ieocxxki.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhgphyol.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gt2pusownjh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddlpkfzw.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gt2wrjlvpdw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gt2zxhbuyfa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gt2xafzzjkj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2aqtctdth.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2kcwfmfsm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbjveiwr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gt2wweyctqj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gt2snnsxuzf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gt2sawpxlnt.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gt2choepfkq.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gt2mambxquc.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gt2suuslngs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2iusmwxis.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiubgygc.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gt2sviuysqz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2pikqwppa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gt2kacnkbpk.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gt2prnigjvk.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gt2iaybcewt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gt2ilkcmvkp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2wwwxeyge.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gt2tqitrcwb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2cjoknpjn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2vccothwf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2biisgotp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zojagrwg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2cyvzhrdb.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gt2vaiznsfc.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gt2vykjigaa.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gt2gkozejrj.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2fdqxecgx.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2wwksuqfq.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2tptjnwbp.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyfovlat.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2bywbnjqr.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2mcfjrotd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2wnhemnjv.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2kxwhxcxk.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gt2vlfqoesi.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2gktyqskw.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uymgsurv.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2znubgnqt.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gt2tclydpst.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyrfvtxk.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ieifrqxw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mqtqalyu.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gt2prrtyhil.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bqbnbqmm.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2dwginfsn.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gt2jvbmyfrg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2wrzwezya.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2ukhaljxr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gisjeqyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2boicitfp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxxrzevy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkdjeebw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lifrlpkb.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gt2mjxelggx.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2knkodcdj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2utrznbbz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wuihurio.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbcwdzfi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gt2rtecpwwa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gt2sitvykek.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gt2hbpnxhjt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gt2zgrtcdyw.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2sjemfghc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gt2ccflpqfe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jkvakxlk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fudikxug.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2iwdqjesy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2ekdbexlr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gt2finqpfsp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2iqbywbzl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gt2qlprlfit.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gt2ccsinojq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gt2dkfjklmp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gt2ewyyowbz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2raboqmfw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2csadxovm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2ghbxkjun.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gt2erqvxbpc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cykpwgsa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqjtlkok.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gt2xfxtduhm.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2onzxspts.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2jstkajqb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2nbdejavz.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqbctzad.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2wjblglhv.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2scmtibkb.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2mzlbjjnf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gt2kdhiqajk.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmkrefbt.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gt2ihrqgkch.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gt2ppauvsjg.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2wznyimti.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2xeoqgate.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gt2eggrpgai.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2xpmxycep.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gt2vamfpofa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2eiwzhude.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gt2gfdsiaam.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gt2xkehryyc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvvofeol.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbqtbkyn.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2urhqzjox.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2jghiugwm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gt2zutuvolm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2aieivlas.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgcorfuv.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2edjaxemg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjytqguo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2ilbtykuh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2lpuxxegb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2tpizgcat.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gt2dcgkmrfd.html


<!-- 参考信息 -->