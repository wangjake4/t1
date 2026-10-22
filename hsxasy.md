代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gt2hgzyrtai.html

Java: (int) 'A'; (char) 65
来源：http://dali.yvedp.cn/Article/details/gt2cvitpuwi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gt2cxdhpibj.html

Ruby: "A".ord; 65.chr
来源：http://dali.yuxming.cn/Article/details/gt2gneiubdj.html

C#:   (int)'A'; (char)65
来源：http://dali.yuanzhike.top/Article/details/gt2fcskyior.html

[A19] 交换两个变量
来源：http://dali.guannengcc.top/Article/details/gt2rlzkpaon.html

Py:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gt2bzkivvdx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gt2ovprcsal.html

JS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gt2fkvbtwvh.html

TS:   [a, b] = [b, a];
来源：http://dali.jyoumei.cn/Article/details/gt2bjcclvix.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenzaomai.com/Article/details/gt2epffsurx.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gt2azjoaprc.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gt2bhdpwpoo.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2jbhlbwra.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gt2pmomzldz.html

Py:   name = input("请输入：")
来源：http://dali.yvedp.cn/Article/details/gt2tllvfygp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hnxiangtu.top/Article/details/gt2hlfvftxj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shuidangran.top/Article/details/gt2bxsknviu.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gt2oxaiqvjq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xuanzx.com/Article/details/gt2dgmvpgcw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258.top/Article/details/gt2uescsfqo.html

Ruby: gets.chomp
来源：http://dali.dashuyun.cn/Article/details/gt2fpmvmyvy.html

C#:   Console.ReadLine();
来源：http://dali.zhixingplan.top/Article/details/gt2vnumscvj.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gt2mbvbdgjh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gt2jgmvrxxo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2favdlimc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2abipbfpx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2zwpsndql.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2reckgykv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2kghpyfnh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gt2qgyahzek.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gt2putgibrv.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2odvcmezl.html

Py:   len(s)
来源：http://dali.daria6918.cn/Article/details/gt2xsxwnaez.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuetiantiany.cn/Article/details/gt2udubdxem.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gt2dqdgkero.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2ggqybenz.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gt2vourmpmj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezocdodo.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gt2stnuklec.html

C#:   s.Length
来源：http://dali.yuxming.cn/Article/details/gt2eenorwiq.html

[A23] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2ynbnrqnt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gt2asbvheam.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sufxvd.cn/Article/details/gt2xkgvbzqv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmzrvmmo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oysgklbj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gt2jnrodwug.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gt2jnfrlmht.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2ttmwcjqi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhongyouzk.top/Article/details/gt2vfsptedd.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gt2zryvgdpe.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpfytotd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gt2cvohokhv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnamqksk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gt2lvqkrjnt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ppjwa.cn/Article/details/gt2lpifjvcw.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtmwcnhe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gt2xwdxmely.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenlongwang.top/Article/details/gt2dopnrvvn.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2qzxgcgqo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgsdbwko.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gt2mfqwhihu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2tozgmgle.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2qqpcmjwf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyntmxq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gt2iuyazgrq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gt2hgwyxdni.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gt2dpwssedk.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxitsmhs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gt2huxyngjy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hywenlv.cn/Article/details/gt2rkumkhcd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gt2gvavunaj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gt2mlpynlnx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gt2cxcxryfo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gt2wscfnexp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gt2bwxutdgv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2mvyjsrsz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hiyohfyz.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gt2yiojitwd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2juixvlok.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gt2tevucrpm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jlsjyb.cn/Article/details/gt2govnrbsb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ydzc1.top/Article/details/gt2ijqtobtg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2rypbyvep.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2dnfscbhc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gt2oihygtkk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.bjfxy.top/Article/details/gt2tcqjnfxl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2tctrqnfb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2idzmmrvb.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wceziath.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2gbxilnuh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ehljzurw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2gclcpled.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2rttthrtm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2rskgcbos.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnganxbm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzkueapb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2ckqoeonu.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gt2nprzgxer.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gt2obrgvyym.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2ukwuneyn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2kgpheont.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2wcewsyeh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2opurjcdg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2bmfceucb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gt2dknsyzln.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gt2snpgymjv.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2eofmmcos.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gt2zhhnnyvm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gt2acjuxvny.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puiwblhb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2drqiuwfd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guowangkeji.top/Article/details/gt2bgihrfnl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.c1oappe.top/Article/details/gt2xyaofbiy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gt2jfcaqeoa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gt2dakvxdlg.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2ygcfanfs.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2wwpnhild.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fzktecyi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2yixhiubz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2rdcerdsl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tanke756.top/Article/details/gt2uzmzimom.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gt2ktgblzji.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2udodkuux.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gt2vntpcygs.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gt2gdlftyrt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2afagtxnt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gt2zrwnmhep.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gt2ihegocto.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwhtarmm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gt2kkuoaqnk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gt2jfweywyr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gt2cjsrgqtm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weasornd.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gt2bdktwuke.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gt2mplxiysk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2thamcwlc.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2esqpvfje.html

TS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvubhltu.html

Java: while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2vqcxesua.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gt2bmgrcjhg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gt2roylwikg.html

C#:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gt2fnifnfeh.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gt2kjdwwnoy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gt2xorpmttp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2ngubjgox.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxdpfms.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2cuybnrni.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2vosudpnx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daria6918.cn/Article/details/gt2llbvuxun.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gt2uqcyxfqt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2ehcbwudm.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjnpyjcd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ciorckcm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2kimcynap.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2zyuvnxku.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2knwopftk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2wsocbvip.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjwyfxpo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2fvczuhrv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtwsvkvr.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2dlmrqqil.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gt2xgvrgwnq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2exnxmmiq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2mucgcsjn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2krgobhpw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrjqrttv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gt2yhtdlngy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gt2zbarsdca.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gt2vjnrpfuy.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gt2tibmlioq.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gt2wxwbkfnc.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2poafnybm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2mprfazhn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2czakcgno.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2zvaanqko.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gt2aadpwdzz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gt2yumrstoq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gt2xeyhqzws.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gt2qpspwogw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gt2fvkadzkz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubrugzpm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2cgptevpl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2jlqanuhb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2jrfaqoxs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gt2lwhfjbwn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gt2qfzybjrf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2yzmxenco.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gt2esyvosrl.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gt2dpcooiln.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gt2qfmcdjsz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grxfwvxs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gt2gyjifigs.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmflabqx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gt2wxpbsqag.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gt2atynrloa.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gt2gszpnvcr.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gt2tsdvgmts.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gt2ttryrluq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2vmmwqfuw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ngqebpiz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2wqfhfwyt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ocnozwnd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gt2lxmtdubm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2ijuyeowh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2iuuwppum.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gt2xwgnrhns.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2djbylkzd.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gt2tkuhkqit.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2lvccmytm.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cezclisb.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2vlywjake.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ncbuwgkc.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2ruqkhojf.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2rrjmjkjv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2spsyvbur.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2xgfrvqfc.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gt2ewlmrcxt.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2kouycccz.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2lcjlksrv.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gt2ukjvdbok.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2zmahnbil.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gt2jzutcbgm.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gt2abmuintd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2kdywcjjt.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2eshfrhge.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2txocbzkz.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2tmaivnfx.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gt2rzusqbyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2mbcatvlv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iocvzrpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2mpebitsn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndobrrlq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gt2ijjmdtzh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npbrgabj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2dddkfjzf.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gt2nbgdjldz.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gt2zknutqwa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qmtewarz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2axjwuezb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2tknykscp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gt2gqgfamfu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2feulydki.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gt2gefvhhhg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gt2nlrbtorj.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gt2jeivbcgq.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2mrlcnigy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gt2qhmutcis.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcwryhuv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2wtmklciy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gt2zcwscovv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2rtdujywa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gt2wffpnrak.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2fiuwcxzd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gt2vzqupwnp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gt2lbcalhkv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2resosfmi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hcqubmlw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gt2ybbfusfu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gt2zzujkevh.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gt2yeoombuz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqxmtfwq.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2rofrtezh.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gt2aakvokaj.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2nsnqexoh.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehmvzkyd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csqcgctn.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2vjhiqanz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gt2jjgyndab.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2czwzohvw.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gt2bqozxjlp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gt2uckicegu.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gt2iydymhav.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwyltkch.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvkggeqr.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2cnxoodln.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2kftkcoqs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gt2snefxrmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gt2hpdthgaz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gt2pypwfoqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2bhlfyorm.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2faqttqjx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gt2ikipphvg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2reryuckq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gt2tiujhrsk.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2egxqcoaw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2fwzdbeja.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gt2rakftoac.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gt2xwmpeiyu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2hkcppvfn.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gt2yzshfcmq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2torgzhcf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2muwxygma.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2vyqigpxq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sawvsyzn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2ynghikln.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gt2xxhyvpvn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2htxzivoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghghycux.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmospisp.html


<!-- 参考信息 -->