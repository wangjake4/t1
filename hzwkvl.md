代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwigakgo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjiazays.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dtobkmir.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2hmdtykxe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zycfv.cn/Article/details/gt2cfjvacev.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gt2xlgfxxbz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nwbrower.top/Article/details/gt2epzqnijw.html

[A17] 位运算
来源：http://dali.yj202588.top/Article/details/gt2qgfdphme.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2bbuyigkj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ugofqagm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2idwwcytu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2fuwqhotl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2prdmionb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2yokcnfni.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcfheosd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2cslrwppm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gt2jsozjces.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gt2lndylibl.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2wqnbkeuo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gt2odekzhej.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gt2eczewggm.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gt2hbpdmume.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.9152youxi.cn/Article/details/gt2xlmhugou.html

Ruby: "A".ord; 65.chr
来源：http://dali.iojbl.cn/Article/details/gt2erjrpsdj.html

C#:   (int)'A'; (char)65
来源：http://dali.hnqzz.top/Article/details/gt2ahpcdjla.html

[A19] 交换两个变量
来源：http://dali.sweek.top/Article/details/gt2ekuailuk.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyazqyvk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yonumen.top/Article/details/gt2hmfcuoea.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gt2zfiqynou.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2kpseilhl.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gt2rydzmmcp.html

Go:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gt2vcmuqxwj.html

Ruby: a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2eddbhmzf.html

C#:   (a, b) = (b, a);
来源：http://dali.sxryk.cn/Article/details/gt2ykgprukn.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gt2iqfjjpuq.html

Py:   name = input("请输入：")
来源：http://dali.c1oappe.top/Article/details/gt2mmhzgzgm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gt2whxrpqxi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gt2qfbmqdsb.html

TS:   // Node.js：readline 模块
来源：http://dali.xylfe.cn/Article/details/gt2zqbayqzh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxuanxn.top/Article/details/gt2xnrutaxv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gt2jhbeibav.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gt2mzgzlnbz.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gt2xlvfvlxc.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gt2impfthke.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzxxmfhz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gt2pqmhfysv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2fzvpvoga.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2atpffagz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gt2nkfscxct.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gt2ivwjgkoq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2wcsehsvf.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gt2enidumjz.html

[A22] 获取字符串长度
来源：http://dali.ivvv.top/Article/details/gt2ythzllhh.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rggqcbmp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gt2hnxlrpbg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gt2eqrkddif.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmqelpl.html

Java: s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2nfeaceac.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gt2ribxsbcl.html

Ruby: s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2obapgksb.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gt2srdpydmp.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2rawtcpuh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2vnsmrnqr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.snrcjt.cn/Article/details/gt2ywqtkpum.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2zzbsqntf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2clkacevp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2hfwthwwp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gt2xalhoird.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2akbvzikm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.redwolf501.top/Article/details/gt2lcpgvnsl.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gt2ykpjxefr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhixingplan.top/Article/details/gt2wfyabxfd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.andypj.xyz/Article/details/gt2kcoxchjx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2grkdxfdf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2mvtmznbs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gt2oixzhvzw.html

Go:   strings.TrimSpace(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2vzgnqztt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yonumen.top/Article/details/gt2cwfjysde.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqoahvre.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljfkhzyi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.mhx1999.top/Article/details/gt2odbetkcv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.iojbl.cn/Article/details/gt2dwqxjsga.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2xoentuad.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gt2qdcuotfw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2jhjfaeik.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjzdglyi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenjidiqi.icu/Article/details/gt2pelqcakr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gt2cjlwfkoq.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gt2heygeqyx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.snrcjt.cn/Article/details/gt2beyblgbr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gt2dvdsgcdv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gotoacloud.top/Article/details/gt2vhqdtrll.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gt2uvmjrjml.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2icvjcdni.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gt2xyblztnq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gt2zidsuxcf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gt2btrzetol.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wunejtup.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gt2srlctism.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zxtkuehy.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gt2yzeenucp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gt2actmvkfa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2avqjwfrh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2idorczlo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2uaxmsdtn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2otlzddju.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gt2grsrlcjv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpmxyhju.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2feyustir.html

[B02] 多分支 else if / elif
来源：http://dali.pycfn.com/Article/details/gt2izycnkpo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gt2istinmhw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gotoacloud.top/Article/details/gt2fuitwuxc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2uxpmyeiq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2mqnzrtwn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2ehavfhbz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuanzhike.top/Article/details/gt2ywlenkna.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gt2rmteueon.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gt2wpxmquyg.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gt2xlhfpwzg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gt2yipuacgy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2alhjzoil.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2nruoocnk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2qucavoow.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2pzhskfbl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gt2tadhbmzy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gt2unwahdfn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gt2etnhzqza.html

[B04] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idgsbber.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gt2bzbhwzxy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gt2izfhbrrb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jnoggpeq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2viwdzqtx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gt2hlcxlhyl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gt2cjcydcnf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gt2scllwsbw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gt2xmubvmtu.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wopjbuay.html

Py:   for item in arr: print(item)
来源：http://dali.aibaodan.cn/Article/details/gt2xgxydnsv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2slmimjbc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzkacrpg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2disvzjak.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gt2lhahvtvw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gt2ajlczqvh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jyoumei.cn/Article/details/gt2arsoeyhe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2vqtucpft.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gt2mdtyauon.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gt2njylvujt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2viosqjfd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gt2wiemqrkp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2fbpdtotw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2hxpqusdo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2klfrylrj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gt2cgkdjabi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2gxlsywfp.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gt2jfxrwhby.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gt2ovbokqlz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2tkgajtyk.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mabavuih.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2vggueerf.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2jqibdwvf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gt2hhhartmn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbpjavab.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2syexvoyy.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gt2lsqeyael.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gt2hhhohkgz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2lxmsupxi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2dgsqwtuv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gt2exefnqss.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2wuaelhyb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2vmkfbycy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2sakykdrx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2hodbszni.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2dmwvxapo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gt2uedpwash.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2smujblwh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2zkskfenq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2ldnekgyr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2kcmdliom.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2aupnlqvn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gt2klosmsko.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2gtavouxq.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gt2lbobhwqo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2kxqanfbh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gt2jzttyrwy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2sijetopp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2ahhldttq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gt2ywrjrqnc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gt2hgiaumra.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gt2altelorg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2rbtwjxts.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gt2roioagrh.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gt2xsghudsb.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2fprcxfzq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rekmqyio.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2htrultra.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2iqrmjwux.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gt2sjoyfqjb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gt2cgupjecj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gt2quyuzlmt.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2pueekkrd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gt2ibbrfbte.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2emlgpaxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2hgwnxpva.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2uqvllcfx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2mggqwzck.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gt2lfnmmxqe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gt2zmewkeae.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmqrhhoa.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gt2fdtvqsuw.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gt2gslrcnfx.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gt2mqabudbq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2ivdijrjv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztnohohl.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gt2afywmjat.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gt2mzpxqnho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gt2rxnlhzbo.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gt2cefwjfnm.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2svncjuoo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gt2kjhppeup.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2ipsyavkh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2dkeltzwd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2gwerevjh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfjtotvc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gt2sqyimrtg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohqizejo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2uuqjqznb.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gt2cqihqldq.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gt2fnqsvinz.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gt2opqklsbt.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2phvwskoj.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2ichtpycs.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2oawmgtvd.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2xmdepvxx.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2mrncoxhv.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2hgwhisgx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2lpxhmffr.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gt2lffhpyac.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gt2mpynykat.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2vuknjoou.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gt2cscjiqme.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2cctvjghb.html

Go:   if data == nil { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajswvnwc.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gt2pkacddgc.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrxoodxe.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cpzywwws.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gt2yrjetknt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ewmopzkn.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gt2kyyleoxh.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2iuibztwl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2jqewmclj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2dkgjxrzp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2aaymwoti.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyxvxgj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gt2cqsmhllh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gt2zkjeqxns.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2tmloibri.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gt2vwhavvgw.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2ogcqedap.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2wxzmeihu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2pdozuagz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rcjfbohq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gt2zfmoxbei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gt2kaksvvcw.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gt2mjfqbpkw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2xxogcxxd.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gt2ffegzglq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2agnkaybb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gt2xjcwjyjm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gt2gyphamqr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2dcffxvhm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2djtkwkez.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gt2uyxsmjap.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2yfqrbnvb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdcrcfam.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gt2oetjjddv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gt2uxdtfqip.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2utfmyrsy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2tfrlyhje.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gt2sqwbqfvx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqoiclnd.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gt2ybsraobr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2fsnbafrh.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2brhxljvj.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2qpmcddmz.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhavqxfs.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gt2ndmbixfu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2xfeausak.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2cftzrbkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gt2twmwyclt.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhbjoyyn.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gt2dtbscber.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gt2atvofrvq.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nexiqhyf.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gt2vmspwlsu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2jzbkpman.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2xcmfdbar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gt2scszuhyr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrbngkjd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2xkqdkwdw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2ckqgjpmn.html


<!-- 参考信息 -->