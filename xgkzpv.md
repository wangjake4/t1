代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gt2mhzbidhf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jlsjyb.cn/Article/details/gt2gcinhskh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2nprhbctm.html

[A17] 位运算
来源：http://dali.hywenlv.cn/Article/details/gt2lvwkuyrw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2cgxgrdnd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ivvv.top/Article/details/gt2bnjezkcq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2zxvjyvnb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2jioiagdn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2lqsliipl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2wdbcthwg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2fkycobzd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2yjcfpest.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yueranfly.top/Article/details/gt2bctmadar.html

Py:   ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gt2rixktvfp.html

PHP:  ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gt2zrobmkty.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2ocxlckps.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2vbgtebzu.html

Java: (int) 'A'; (char) 65
来源：http://dali.quarkkingdee.top/Article/details/gt2bqzrdyfg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtsnehzt.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gt2ifxhovfo.html

C#:   (int)'A'; (char)65
来源：http://dali.havefunace.top/Article/details/gt2yikbrvve.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gt2ymyahzgo.html

Py:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gt2aktcbmcw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gt2gjiqjdug.html

JS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gt2fsifhuuk.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gt2jbvpmeno.html

Java: int t = a; a = b; b = t;
来源：http://dali.0kj1m.cn/Article/details/gt2zzwzgvmz.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2qrutdesv.html

Ruby: a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecsqjves.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gt2rqomzgcf.html

[A20] 读取标准输入
来源：http://dali.hfpthk.cn/Article/details/gt2mzeaebzg.html

Py:   name = input("请输入：")
来源：http://dali.cdnleiting.top/Article/details/gt2sfubdbet.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xylfe.cn/Article/details/gt2lodkdfto.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigfzy.top/Article/details/gt2pkvuazsd.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gt2utywkhyy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guannengcc.top/Article/details/gt2wpphbvts.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gt2vihkymxd.html

Ruby: gets.chomp
来源：http://dali.chenjidiqi.icu/Article/details/gt2flkxfjri.html

C#:   Console.ReadLine();
来源：http://dali.dashuyun.cn/Article/details/gt2vxeskwho.html

[A21] 保留指定小数位输出
来源：http://dali.andypj.xyz/Article/details/gt2ktwmetpm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gt2rjvsnbzw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2dkuwrwgw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2lcdsxtmk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2tfjzctfo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmhyhzyy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gt2vjprdpsd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gt2lwqlchea.html

C#:   3.14159.ToString("F2")
来源：http://dali.cdnleiting.top/Article/details/gt2rdjxxket.html

[A22] 获取字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2hnkwfjnv.html

Py:   len(s)
来源：http://dali.xuanzx.com/Article/details/gt2thikiafq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gt2gcyjgkfn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuanzx.com/Article/details/gt2phjcdnzy.html

TS:   s.length
来源：http://dali.c1oappe.top/Article/details/gt2odzfawqq.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2vspdvbii.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gt2rqjxaqcf.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgnxkgqr.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gt2qflhsfxz.html

[A23] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiozxgoe.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gt2oqdhkiwm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cheryme.top/Article/details/gt2nfwfimry.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gt2qsslvsfl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2tewvhnky.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gt2djtlftqe.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tswbeqsm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2ezraoplr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzzztqrt.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gt2aethzngb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gt2mcpwdzhj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gt2xpaerawu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gt2lszkxhhd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2lzavphte.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sghfbpfc.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gt2xzxgfzfi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gt2ccixgeqd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2ysjayriz.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2ldubpznd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymmhkxdx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gt2xowdzciz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2canyxrgm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qaglpijj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbiexyhv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gt2txpkgkck.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gt2fxcdouga.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gt2tfbrcrfm.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gt2nzuxbavj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gt2wrlfzxpk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gt2laerqzdy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gt2xqkmrojv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gt2dnlzqiwr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gt2qbdmvuee.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gt2jkrpvwdo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.iojbl.cn/Article/details/gt2yiknqmml.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2hyupgeik.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dgzzgafx.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaqeqqd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2pnoldtbd.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpeaumuo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2yewhsldy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gzhubu.top/Article/details/gt2eifhmejk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2pfvkruzf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2iidjcqij.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2kxjrazxc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayzeoaqz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gt2ucazxyqo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2smhiprxk.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gt2batxrdxo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krzpyfft.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ewbxpyyl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2jgiwagkl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2sijbgsid.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2mmhkytiq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gt2zvxtrubx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anfxtxyq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2tnxtaoac.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkjmldjt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gt2vyavkavd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ixhuzwpe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2qwwwlbcm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kgsgjxvw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbafihoc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2wypodywy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gt2jwjsibsp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gt2myuewbqv.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2yasmltio.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gt2mbuphlfa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hqsercfv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gt2ywyxrdho.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2iljqaaxo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gt2mmkkuryx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gt2wrhnbjnn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gt2ucizknvw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2ixiieuuc.html

[B05] 遍历数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2skzryadb.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gt2fesipqnh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gt2ipfgcbvf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2whfdvswo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gt2rtholdly.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2crcogunh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gt2eulxkwrn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gt2qkgtjvss.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myejqznk.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gt2bfguzatu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gt2wiiynhcf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ztalzrhw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hszsgooj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2tgizwcax.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2voiemruj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gt2pthamfug.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gt2fwojgbxv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gt2tvigsjkp.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gt2zlifgmqb.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gt2gsbxbwzz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gt2ylixlbfs.html

JS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2awszjiyl.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qvzvppus.html

Java: while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gt2yxscmjel.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shuidangran.top/Article/details/gt2czoudhxw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gt2vsqynjfd.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2sapotaze.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gt2iepzotul.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gt2qkdrzvcp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gt2sirdudrd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2ciylhtai.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2qzyuwpnv.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdnsrfdg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2klkgtekq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gt2zzceuoov.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2avfqjmgs.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gt2mjxdnvin.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gt2hjkbvwzm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpbpfgbf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2ihgzwrgo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2zxsdfwas.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2dydsoixe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikdbuwxn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gt2xeqpggfn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2tbqpwhic.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gt2oucjnnxc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gt2ecayjqgf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gt2yqwvruyk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2agnwcfkw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhexujym.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gt2ryzfyugd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gt2hjghbfrb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2doxwhwik.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gt2kdnmzyix.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gt2rbafvkbg.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gt2bdqzxoit.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2neorlvpa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbgukuor.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2sdlcvbop.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2glfnsyyg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gt2cpiydoqn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gt2rpexgqnx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gt2hozlapru.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2nazxyvir.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gt2oicsmszo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gt2xlxdfwfo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpnljtjq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2meqhiaoi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2ywsfffzi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkcjluja.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gt2bojirtag.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2zqiobwgo.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gt2lirwhxtl.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gt2ihbnkybo.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qvzaqltm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2ucmyxwcd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2iebtllgz.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gt2mtxwyqdh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkziqvoq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvflqpwc.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gt2ovihmfzj.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gt2rrfvgjvs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gt2qaavqlwq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gt2ruztpejt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2apqdqnvp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlovijcw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ucbjpqpl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpjsvnwl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2zporzqlt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2xhghwppg.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gt2uraaykeg.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gt2obsiobco.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2qcrztflh.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2zbqtfdvc.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2keepiljh.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2celnwrno.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvzyrztc.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2sydnaxqu.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2satwjaoc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gt2lvmyofuy.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmeglwch.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2broysxvf.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipaxmgvb.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpbhlits.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2eqtgujhs.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2kosxljmj.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2sayzsylv.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2zfgjmpjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuqytvx.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gt2kgwopqlw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2azwyatpd.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2upkyrudr.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2njzaqytm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2gafmjlme.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rbbddulk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2zsjqibmr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2phblbxqz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2ioinauct.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gt2bwkdvijh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2jcwxsrdc.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2dbaerrol.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gt2mrzuutol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gt2swmqhxxr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2yierzqll.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2sqmpbxvr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gt2iyvtybbk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaflssyf.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2cdvzcysu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gt2tnfsppqw.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gt2gbdmjdic.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2ajfixhrb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2arurebmw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2oepcuqzg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2nmyadgdu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gt2irqotdiq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2netvzffn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2vjjpwjbz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gt2xovfdsmb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gt2beinhwti.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eizdcjnv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2htttrdur.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2wcqxmvwe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2lxcvecxs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gt2hpjcdgdj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gt2xjawyekp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2dvwkfwuj.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2dtbwxhie.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gt2afkhaska.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2mxhjkyst.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gt2qbrtcxbt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2smxzmird.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2opyhekyo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gt2ipnmmary.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2edokuwlc.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gt2ammlpewz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gt2rocxqbuv.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gt2jxhcldor.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gt2kmkjzoma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gt2rxhjfeye.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2kiholdhd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2dlxcwetp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2jyfbygbv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2vlzcnico.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2ddfbnwgb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2jcwterfg.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2wdfxqmcc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2kxydhonc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2qmcvkyyh.html


<!-- 参考信息 -->