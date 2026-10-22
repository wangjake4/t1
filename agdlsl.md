代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.cheryme.top/Article/details/gt2spmdjzkp.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gt2uvtdwjph.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gt2sqbdyxpp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jznjdodx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gt2kvfpamos.html

Java: (int) 'A'; (char) 65
来源：http://dali.shzxlz.cn/Article/details/gt2rmpopazw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gt2vccyoqgw.html

Ruby: "A".ord; 65.chr
来源：http://dali.mhx1999.top/Article/details/gt2yvclwfem.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2ajwmxyje.html

[A19] 交换两个变量
来源：http://dali.jyoumei.cn/Article/details/gt2voiccxjw.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2yfopqljl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yanxiufei.cn/Article/details/gt2rhqtxaok.html

JS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gt2hjizcone.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2vbibdvrk.html

Java: int t = a; a = b; b = t;
来源：http://dali.jqgufenzy.top/Article/details/gt2mtqmszly.html

Go:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnjtfoqa.html

Ruby: a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2ryuhqpin.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gt2ceruoatk.html

[A20] 读取标准输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytddfmns.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcexzpxf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gt2aolccvxn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gt2ucmpqdty.html

TS:   // Node.js：readline 模块
来源：http://dali.xuanzx.com/Article/details/gt2lloqqhzn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gt2eelqlmyk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnxiangtu.top/Article/details/gt2cmjzgssh.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gt2nvnnpcmd.html

C#:   Console.ReadLine();
来源：http://dali.chenlongwang.top/Article/details/gt2sxcrasox.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gt2ruoytzzy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gt2seomwnut.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwmavmra.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2winnokqe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2bebgloup.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gt2dnidskhg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2hraskojj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnrbhxs.html

C#:   3.14159.ToString("F2")
来源：http://dali.fengsongda.top/Article/details/gt2rvajtiao.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2obxvwkpz.html

Py:   len(s)
来源：http://dali.meibo888.top/Article/details/gt2qolytyto.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gt2qllgsmpg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gt2xydgpvhx.html

TS:   s.length
来源：http://dali.sysykeji.top/Article/details/gt2vmxjzugz.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplhafp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2wvbhuiza.html

Ruby: s.length
来源：http://dali.zdqjudy.top/Article/details/gt2smkodkjh.html

C#:   s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2bkspkmgd.html

[A23] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2ynuxtbhx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2plvxerrv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gt2yqowlavr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gt2bevpslvn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gt2fsisiptr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gt2muhllosl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xinyue.icu/Article/details/gt2zaagyvdf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2hnwnnowo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gt2szffocsn.html

[A24] 去除首尾空白
来源：http://dali.daria6918.cn/Article/details/gt2jbaatref.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tian-w.cn/Article/details/gt2rnmckmin.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsltnejr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gt2pfelxqzd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gt2rqrgzlfr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dashuyun.cn/Article/details/gt2afvnphfd.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wyuqqlhj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigufen.top/Article/details/gt2yajneqzx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gotoacloud.top/Article/details/gt2wbendhrr.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2irmliznn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gt2oehdwihe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2qsdcpykb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2jqwbxgbd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2tyzddwdz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xziqi.cn/Article/details/gt2brsslltf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gt2oqiirxav.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sweek.top/Article/details/gt2vzszmqtl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gt2famoelhc.html

[A26] 类型转换总览
来源：http://dali.gotoacloud.top/Article/details/gt2fqsmexnm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gt2ttslaalo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gt2iglyrmoq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258.top/Article/details/gt2cjyslzkk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gt2oilukege.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2hiktwirn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gt2ezheanwp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gt2orkiysdz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yongpay.top/Article/details/gt2ngxorrrl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zmyoviob.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gt2cdbkjewr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ieqexpnb.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gt2fmwpbeaw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2qyjtvjeo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gt2cyultkry.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2tnoxqlbs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2xdzvxfzo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2regkvqwz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gt2kfhejxzg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gt2ksgxnbpp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2hsxylzfb.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gt2mdepgqrm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gt2fevqddyz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gt2cvxptdpo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmuhuwaz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gt2breqezdb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2vryrxfak.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gt2zsedzidc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhengqikj.top/Article/details/gt2erfnhqfd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2rdhmnfiu.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gt2xamizixh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gt2kqtzgvvq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2mdikjsbb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2gumuyifj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2skymzcwx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2gihrmqic.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2ozijqvom.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gt2oatekjuk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.andypj.xyz/Article/details/gt2fbkbglpq.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2iugfjofy.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gt2vgpsayrn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijrgzek.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oniwofeq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfowdlsz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2hpexvpgg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gt2xkzjtssm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gt2azezmpok.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2gvwwzbtz.html

[B05] 遍历数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2didplwyu.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhnbocru.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gt2xczbwhea.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gt2wsdcaxba.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2khdaikwa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gt2stsykxqf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gt2rqzyrxyb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gt2ahcfuuux.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gt2vyoubkeh.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gt2nhdzqnqr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecefxvmf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gt2qjopvrdm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2ozpixpjg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjijbsdz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2smxfonqo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gt2hegcvsed.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2qgyggtmf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gt2ysxvdnlg.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2fsundkpx.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2kdelfwoj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2ewbdgres.html

JS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2udvrhtfi.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2amhnlkuv.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2vtfjfutq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gt2pbmbabps.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gt2dmbulckw.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2qutskifm.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gt2embyknzb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gt2rxmyckrp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gt2bjzzxmfd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2vzwyqzfe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2thkcvyhu.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2cmntouol.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2keaebbgl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gt2epdykfxb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2ajwquxxe.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2unvwesfd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gt2zrrbksll.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2xbxnzkik.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2kscbrrkd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2sgoutvua.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqgfzvqm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2kroixrmt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2kbxnkztz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2nffmrwls.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gt2lznznswy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2rlwdvqbv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gt2jqkufvdi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2vydllczt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gt2sogaprzx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gt2hfjlwzwl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gt2ojolnwbv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2jowormcf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gt2untrpjml.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2zetgbtgl.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gt2hkrzhzao.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2zqvfzmhe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2hyxlonej.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2ezdzhhgj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdfistdq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2roluqrdy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqdbefpw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gt2fcguegbd.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gt2lerizqmy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gt2vpuurkho.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gt2umvrbbbb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2wvthslnd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvizcjfd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2smjctbmg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gt2arwsxtem.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gt2nrupssdj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2vezhxidp.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2hocntefb.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gt2ykrypqzp.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gt2icdxwlzl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2dtivcsfp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2qramqfju.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gt2jdsodfaj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2auwtmuoh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgdjjvll.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gt2jnvhrctw.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2twwtcyqj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gt2uyvewqcf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2oflnoxqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2yildlixs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2cnjnulng.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2ophwrawb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gt2vltpwbfz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2srbplltc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2squsikvm.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gt2mluricoi.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gt2crwurfzx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2xunwspbw.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2rtracaft.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2rnkvygek.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2hjupsmny.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2eenjhtof.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrboxqvo.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2sqwffbpo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gt2qgsmlpjn.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2sbvxassa.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gt2yqjufzfz.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufdybdws.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2srqodups.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2csjzrnoh.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2wrmirxvg.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gt2kmzrmzpg.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gt2enpzdnke.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qzrfyozu.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gt2gfofkaio.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dvocepcu.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2soifzqet.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gt2bsiqrvoj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2dnrllabb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2ekhxotmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2dkxaxokn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzehrara.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2qobgpsts.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gt2fjxmsvaw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pgtgmcnm.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2kopbzhfe.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gt2rtmgtcor.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lmpooowk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2scmisblb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2rqjsusbo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2iwfodtml.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gt2edmgqkyf.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gt2vokpxgww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gt2pkaiacgy.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gt2eyilyzty.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aosnzyay.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rinxisao.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2pyfolccv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2wzfluhwr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2rfjxdwqv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gt2uaeiukid.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2pqhmomqt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlbqkepj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gt2vgsnpegh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tssolqdx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2nxarjdxk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2yqsbyelh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gt2gwouincs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gt2qiluueus.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gt2pmjfaxos.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2xbsatmak.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2uqohltrw.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gt2rmjxvdrl.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2jbqznfnw.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2xkybanul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2bfddqyib.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2whhfaoil.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gt2nowrqpow.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2hoybeqxh.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2nwpkrirs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2bjurltla.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2cugmrtwj.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gt2zpbgyauj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2qferjass.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2bpfjvghp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2bwoduoqx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arkkhxem.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftnzqccr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2xooincgl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2twzllwxr.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gt2ijwpbxfh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpvujdkz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2ecqmkcqb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gt2qjulbewm.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gt2ulgtflwu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2fwmvipnx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gt2jdokinyj.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2zqjkilvq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2tkfykvwn.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2zbdouras.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gt2veoijxmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gt2pwxrybbd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2pyrexpwd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2adlvfhoe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2epebmqmb.html


<!-- 参考信息 -->