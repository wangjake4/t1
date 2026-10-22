代发 wailian999

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2ejhodyqo.html

C#:   (a, b) = (b, a);
来源：http://dali.tian-w.cn/Article/details/gt2mkbygbvh.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gt2iwxavtra.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gt2xlfhoggq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gt2badnlvuc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sysykeji.top/Article/details/gt2mstsmyxv.html

TS:   // Node.js：readline 模块
来源：http://dali.zhixingplan.top/Article/details/gt2rnqtdxlk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gt2aocgwono.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gt2ebzswvyq.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gt2moszkoef.html

C#:   Console.ReadLine();
来源：http://dali.zhoulong.xyz/Article/details/gt2aiehinlp.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gt2gwqbylih.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hfpthk.cn/Article/details/gt2zzibpame.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gt2dtvqtmef.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2phzhpfmi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2mccblspm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2evnxeskj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofejbrlq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2exftgygk.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxfviypo.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2qhgmmmlb.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fljghbmw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinqigfzy.top/Article/details/gt2jowcklbg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gt2hiqxsofm.html

TS:   s.length
来源：http://dali.daria6918.cn/Article/details/gt2jffxoqys.html

Java: s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmzlynay.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeuhtxpl.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gt2ozcnogsz.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gt2dysgvwud.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2wungwkpn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gt2zauknayc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gzhubu.top/Article/details/gt2ymvzvhav.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gt2itedwcnv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2cmfvwtec.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezxkuvat.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ippenbjb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2seqozowo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhcoojkv.html

[A24] 去除首尾空白
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hffyensk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smyttjyp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gt2cpyjbumy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gt2ecqvbuja.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2aeyhppcx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxinkj.top/Article/details/gt2oydyfieq.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwshyctj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gt2yaondrlu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2ypnfjcma.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2gugddmrh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gt2lzylzweo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vchztbhz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2mjdgtsok.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gt2eqobqlww.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2bttgpbnd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gt2ehprfyzh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gt2wvnlgpck.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gt2yqgxilyl.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gt2fwvpsxgt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gt2muecijmq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gt2loiaespc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gt2phcradgd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gt2iynghbyj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhocpyns.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.vqdsnc.cn/Article/details/gt2sdpuornx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tian-w.cn/Article/details/gt2tpmewzzm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2pwoeyesn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thotohog.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gt2bmumlqnj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dkhzhsoc.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gt2trgtbwvu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gt2sxqokrcc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2clbsdlgm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gt2dgpqihld.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2ogiizhal.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2ujmqptme.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjparwko.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cucudq.cn/Article/details/gt2yhbrsoaz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2ipklahay.html

[B02] 多分支 else if / elif
来源：http://dali.ydzc1.top/Article/details/gt2xzliunxw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gt2nbtkkyoh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cqqwz.cn/Article/details/gt2yzhzozaw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2rqffipik.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2emgwhlrd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2ideabthy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gt2yxjmzshi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gt2xqrorgul.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2qpbualxz.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gt2ctdsfczm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gt2tyucserb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2wfpepsex.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2xlxowgnf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gt2wwbqvvkj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2hnvuugzo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gt2rscqdtau.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gt2jxxnqadd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gt2kjeznjvf.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2kmjfiaxh.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gt2wzcbdvow.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gt2nntwqoym.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gt2hxndrjhk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gt2vpitewal.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gt2rezshicf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gt2ddvralvj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gt2lnipuajl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2uikljzpr.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2neugwwfo.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gt2tgynubus.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2mwzmdfgx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2ragfwacp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2flykfxfe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cqjcjuyg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gt2zmramezl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gt2ctmjhbkr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gt2lfdncqbp.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2hwrmhgex.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gt2wmcgedpj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gt2wgursrvm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gt2wekqfrrm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gt2wgjiedfq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2owbmastu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gt2aqfjhedu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gt2oykjlfmf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gt2ophrsiyp.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gt2lwmyqfyk.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgjitqqj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gt2dfjfwzkx.html

JS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2mqgzplft.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2pwrnmnqm.html

Java: while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2mddlifwd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gt2jxaokxin.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkiuwtu.html

C#:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2utoimngb.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gt2xkzgpemp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gt2allultgr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2uizcumtz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2ohpuetbl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2sfvvjeek.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2qkxqtgtd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsbisiaz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gt2lzlergul.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2dqqejufm.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2eviiifjc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdsmptze.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hawgwrue.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2gnjbhuti.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2vdduoxgm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2ytbeoouh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2wysizfns.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aizwys.cn/Article/details/gt2orldkqui.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2wugvwscj.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gt2leamzqtt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2laafgrkq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gt2kxayvcys.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gt2jflpxfgx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqnwcmvr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gt2xdlpwlby.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.kuanghao11.cn/Article/details/gt2xubibtdd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2wsjadpie.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2kgzljtdc.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2ehmyhdlj.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gt2amygqapq.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gt2uzqlmqop.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2mnigtrbs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2bonfquwj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gt2jxmkdunh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gt2dxmbxjrs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gt2zhpjuwdi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gt2lptsigit.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2xmurzcbw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gt2bxmpwvyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2msajyfvx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2wgwdzsht.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2igtzsztf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2nksanimd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gt2bfuhqjri.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gt2avmhqaqv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gt2deevbfes.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gt2kzaykbww.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdvcvmoc.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gt2wduokdcm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gt2haooomgw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2wgkuhxgd.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gt2gpquglxu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2xpdpxudn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gt2kdgogxog.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gt2mjypkydl.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gt2uzmqyxjm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gt2qzcgwiwp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gt2fsoicbqz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eifapqia.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2pqjtapzo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gt2hbziuigw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gt2evxugiwq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2tljigzaf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2kdfqtztx.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gt2gbpvzkns.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gt2hbwfegdt.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gt2zindtshk.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2tpfloiol.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2poriudcx.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pynhvwty.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2mvnljffu.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2bdztvpqm.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2pwjrcjfc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2fyppiuii.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2qprualpj.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fyiqzjps.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2wynggkuk.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gt2alzzobgf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjpwejr.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gt2kubkoore.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gt2gbiquxsc.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2vduqaxrt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qzmpakfs.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gt2gqnuxqjc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2gtjytgbw.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2vxfybgxq.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2gyecohbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2eetapqfa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2zirumgkp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2runckkgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocizagal.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnhokxby.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2ivgzfpzf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2mtnsmqze.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2cawfplqb.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2onbcxhbm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2izlmjvrw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2tvucxxbr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2bntqydew.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2dhxvpqtn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gt2exuwkvcy.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2rmczvctu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpkefokt.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrfiencm.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gt2wxvdrfrm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2lxibzott.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2msskpeql.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qjcaoigf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gt2qgsbtfpq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2japfsaxb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gt2bjqiattz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gt2nxjvguqr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2nsumtcoz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2llkswkpd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gt2ykokyozm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2vpsrxcth.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gt2vffazjgv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2pmodamnp.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gt2yyeketut.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2xibdnkar.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2kfwkkhjh.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2oeozbbtz.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2hgqfbaje.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gt2ruaaenyc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2dauaugtb.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2uxegdoak.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gt2wbptjxdg.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2bvhpkcsn.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2nshelfyj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gt2jhpjshuv.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gt2mvhqgbse.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2cbsfphrm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gt2irurpyaq.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2bxmahzjp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2wdentepy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2kpzwwhto.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2yngeyogd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2xshpnlbu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2yfpgzabn.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2aktilnyz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gt2nzsivyew.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2aubtakqq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gt2xgdshoim.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gt2macjmhml.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2wzyhzdtm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gt2cyznczkh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2tldliuzg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gt2rwhaeapx.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwiwzlyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gt2tsopvvzq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gt2fqkkgfxj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2lrdiafkl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2xawbtgrw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gt2pqqekduf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2kytadsgd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gt2bjlauxqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2qhujkkqz.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gt2yjvcigwp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2bljclrny.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2caubzqmd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2btdsvyzz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2soltjbtq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2nhsrprgd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gt2fdpmxqtg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyoqvtum.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2wvnkbpkw.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gt2tqgnqijo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gt2xqaamcro.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2qnlyctgz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2sajamhac.html


<!-- 参考信息 -->