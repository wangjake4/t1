代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2ncdiomse.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2boqqkcds.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2olfzhpdh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2jdgyfsws.html

[A18] 字符与 ASCII 码互转
来源：http://dali.0kj1m.cn/Article/details/gt2gmdjbyfg.html

Py:   ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gt2hsempepm.html

PHP:  ord("A"); chr(65)
来源：http://dali.iojbl.cn/Article/details/gt2rlhwgcwq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2vgzbdzwa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2noanzsnm.html

Java: (int) 'A'; (char) 65
来源：http://dali.daxiang520.top/Article/details/gt2pgqhzkqq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gt2jibwfhnc.html

Ruby: "A".ord; 65.chr
来源：http://dali.redwolf501.top/Article/details/gt2fqwtbzrd.html

C#:   (int)'A'; (char)65
来源：http://dali.birdmap.top/Article/details/gt2ijvabexl.html

[A19] 交换两个变量
来源：http://dali.0kj1m.cn/Article/details/gt2hsnqsmwz.html

Py:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gt2sbtxnaqq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gt2xyttpoxb.html

JS:   [a, b] = [b, a];
来源：http://dali.smart0.xyz/Article/details/gt2aoamojfz.html

TS:   [a, b] = [b, a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niprisop.html

Java: int t = a; a = b; b = t;
来源：http://dali.redwolf501.top/Article/details/gt2uhrzxrdy.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gt2hrtuhtnt.html

Ruby: a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvdbodwu.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gt2exkemtrt.html

[A20] 读取标准输入
来源：http://dali.wangdashe.top/Article/details/gt2bqznonsy.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjghnaak.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sxryk.cn/Article/details/gt2kowyzztd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gt2qfzielme.html

TS:   // Node.js：readline 模块
来源：http://dali.haohaochexian.top/Article/details/gt2fzwlejai.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxinkj.top/Article/details/gt2siyyuqql.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szdxuslm.html

Ruby: gets.chomp
来源：http://dali.jinqigufen.top/Article/details/gt2idmeqxbz.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gt2smtxywwc.html

[A21] 保留指定小数位输出
来源：http://dali.xylfe.cn/Article/details/gt2pmbrngjd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigufen.top/Article/details/gt2tecmopih.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gt2bgijjtwd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2fyxnlphh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2ybpgekyi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2xcyzjfnl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gt2qlatqweu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2kmbhmnsa.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuanzhike.top/Article/details/gt2biuqmnih.html

[A22] 获取字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2msvkqjai.html

Py:   len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2zcfqgolf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aibaodan.cn/Article/details/gt2fcjkiikz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenjidiqi.icu/Article/details/gt2agadcqug.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gt2amvsvook.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gt2ktbtmros.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2oyuxahnq.html

Ruby: s.length
来源：http://dali.0kj1m.cn/Article/details/gt2dnvgnlmr.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gt2ociglcdm.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2bklnxkod.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2lfpvmvol.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jiagoushi.top/Article/details/gt2sljvjeoj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2fdmpxnww.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2qosszlrt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gt2ltuvsqob.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gt2nrjnmtzb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2qxbrylen.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pccvmqud.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gt2eycsletu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuanzx.com/Article/details/gt2odxiqcbh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2lsjygsta.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gt2gpmqwqes.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2nmwxkwzj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gt2mddfhkyy.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gt2hrdnveax.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gt2wfhvduzg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yvedp.cn/Article/details/gt2dmkknodj.html

[A25] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2qgfmefiq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gt2yeqmoiej.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xylfe.cn/Article/details/gt2flyagpfg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2vykaotny.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmcvoguh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2diymmzrk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2jrfiqmhe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gt2ruqohwnu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2auiwlynm.html

[A26] 类型转换总览
来源：http://dali.sysykeji.top/Article/details/gt2jitmnoeo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgufenzy.top/Article/details/gt2idpucxfs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gt2klehxmmj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouvzuiyt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shzxlz.cn/Article/details/gt2nemrwqfy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiyddwv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhcqzynu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gt2qjjmhflh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2eiqyvaid.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2glttxzlb.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gt2srbvdkym.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kpzigwjz.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gt2manberkc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onfwqvgf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2acgthuef.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2lcfkjinq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puknqmcv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2dnisjerx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxbzxvtz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2iolxxccy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2fejoibpw.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npaydrpf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gt2iyygfzvn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gt2igzxwdur.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvoenym.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2fpndzrzk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fumjlfur.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gt2ukklimzw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgufenzy.top/Article/details/gt2tfavjvtz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2wgiqyasr.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gt2jzayxyyr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2wnzypyge.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2rxeacsod.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2odohfffq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2dinxsega.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2kuqlxrxg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2lgowwnxv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gt2xcoinwgc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gt2kxodjylw.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2rceuduhv.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gt2slzlspah.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yangfankeji.com/Article/details/gt2tibqjyrz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2ifcconjq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kotbmece.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2cimcefnl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gt2daqgypnl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gt2oqbeapyo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gt2ivpyyzfi.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2mneujemd.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gt2mgelhdor.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qkyeuniy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2pnoyntgl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttmwgsff.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2fxyuclku.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gt2nnmqzfde.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbasskvc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ojifpwlg.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2eblozclb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yangfankeji.com/Article/details/gt2lkuzuqsy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2libfzmjf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2vrdoagay.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gt2srwvlgrh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gt2wfgkeove.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.birdmap.top/Article/details/gt2hvyeoqks.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2cqyevywr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shuidangran.top/Article/details/gt2txkwghub.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gt2hcmmyydr.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gt2angrtuvu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2ueemyfil.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2vzbkwpse.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2ztuddrhu.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2iklvedra.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gt2yuooqqjb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gt2ymuleyri.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2sxltzxhv.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twluxjxy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gt2vzgqnhsy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcvojiid.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2sbaefnef.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2mgxtbbde.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2ygfftsyp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2usmoulzw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gt2iimbruys.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2npmrigfg.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvvhead.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gt2fwnwmipw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2zmrimfaa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2vsdlyami.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2jdvkpljn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2xpshspmd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gt2dxwgxdgw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gt2jwjxavft.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2cloiuidx.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gt2flvwjxrs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpwtqgpe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gt2papvwsrh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2ywrjfjys.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2vvupubtl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ciekhxxe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2uewoyfse.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gt2tszgmimz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gt2sbhlrikn.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzqqdcao.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2kiwothko.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2damtzbgp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2gxmahlln.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gt2pqudrtan.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2clmsdtdg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2glcjlgyq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gt2lgwctmzy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2ufbyqzlu.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gt2yhtqrrzs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2jatmwqio.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2dnrauafo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2lxusszgo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2jxuoteid.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gt2vekmjvlp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gt2czekmoit.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gt2nrnlsgqr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2ocprisrs.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gt2sioqxzgr.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gt2lbnwbcyr.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsheolfm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gadvxewt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2jshovbnh.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gt2jyjdoaav.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2yaeusbdl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gt2wglmewcs.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gt2irummqjp.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gt2pcquwoob.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gt2iamfepjd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gt2ywllxbtw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gubtuxfl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2kxzupjzy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2iqzfengs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gt2skthtwim.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ueelkflj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2ppyxbfho.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gt2pnggkihd.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2zxpxknnz.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gt2cvfxghdw.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2cswhocgj.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2onhkmwgu.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2koacpgow.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2pgzrvweh.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2uwbiynmr.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2glqkqotd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fejeefrk.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gt2dnqpjacd.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gt2wizgtzbp.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2abtlczta.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gt2lpqoyrwb.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2bkkdbdzw.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gt2btehxrod.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gt2gpqodqak.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2saiuzzxf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2uspvifto.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gt2bzgoedbv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zdueghog.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcwrzbzu.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gt2pugmaije.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2fkkduhaa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2mlsggncr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lugddaub.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2tdgukqjq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcnaqfzo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gt2tnnkzysg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2gfnifbpg.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2cunktrum.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2ocjfnbng.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hezginnr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpphuenp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2rtulvxva.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2wsqrpuam.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gt2iojwrxcb.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gt2iacmcbpk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gt2umzktyhx.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2owslxcjh.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gt2nfctlziw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2xlfqtumq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeernucc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agfnzbkq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gt2jwgvgivw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exdgaius.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gt2kpblvyem.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2eplpivpd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2xoryobmg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2cxgovsxp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2itcdqulb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2otqepzbc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gt2jzmcctux.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gt2gshacsvw.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2rfqfzqsy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2qrfbfgak.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2lndbwqnm.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gt2ixfaiypy.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2wnzonedl.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gt2fxzidryh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2alelwvhs.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2wjyvphxz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gt2fvqtqlhv.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tiaefndb.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gt2quwoltfu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gt2sfevhyae.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gt2paynysts.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2aivagwmr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2zxqlcsig.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2gahvmkkz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2nkymhzum.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkhnayfq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2eeiyxwhc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gt2jjjogveo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2wenxwcrl.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gt2ffrdcogb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gt2bzhounly.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2vsosjaii.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gt2ppvuvmrf.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2efgezkek.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2zuxrvuvw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgxbmelv.html

Ruby: arr.map(&:upcase)
来源：http://dali.ppjwa.cn/Article/details/gt2vaposnaf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2pfmkkvxt.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gt2vpahhxbp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gt2mdkqhigq.html


<!-- 参考信息 -->