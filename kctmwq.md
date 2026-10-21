代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gtghudtggm.html

C#:   var value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gthbpxhlow.html

[A16] 真假值判断规则
来源：http://dali.gogol.net.cn/Article/details/gtpfeaywbn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouahjqaw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yuxming.cn/Article/details/gtkvhkivgb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jyoumei.cn/Article/details/gturvgaxgv.html

TS:   if (!x) {}
来源：http://dali.yonumen.top/Article/details/gtxhvllzuz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfowzune.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hfpthk.cn/Article/details/gtjzwrjeir.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gtszvvbink.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cheryme.top/Article/details/gtwlnbxxve.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gtmhtefkeu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtawgjbyuv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxmajlyl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtlmetrmqc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtxbgdecmo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtdtpyfnfk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtzjeennli.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtukxzjvcc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtmnlpprvp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.svipenyu.cn/Article/details/gtlrknywdi.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtxqeyuynl.html

PHP:  ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtbctgtwav.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtoqibieud.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gteojnsaub.html

Java: (int) 'A'; (char) 65
来源：http://dali.fengsongda.top/Article/details/gtcbvlvnxo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofrugosh.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gtehqmoitn.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gtvtrqxfjo.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtoxwabzbz.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjgzgxgl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gtflymeuuc.html

JS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gtknxrfypf.html

TS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtmggppoha.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258.top/Article/details/gtajhvbmgx.html

Go:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtrvjrkldq.html

Ruby: a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtdnrikugy.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gtqthyngqo.html

[A20] 读取标准输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhwdgrvm.html

Py:   name = input("请输入：")
来源：http://dali.tianlin.xyz/Article/details/gtdvvrilld.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gtnigtohuw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gtlkmiarua.html

TS:   // Node.js：readline 模块
来源：http://dali.xinyue.icu/Article/details/gtplxbagjv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gtkyjzcpsp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtzhicvsch.html

Ruby: gets.chomp
来源：http://dali.nwbrower.top/Article/details/gtbetcaqje.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gtjoackups.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtcywqhjcw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqugfqflv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtgqykxybl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtyrdetwcy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtqkyrefky.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtvoiylopl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gttkbsuary.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtwpetzhap.html

C#:   3.14159.ToString("F2")
来源：http://dali.gotoacloud.top/Article/details/gtkklnrjwj.html

[A22] 获取字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbmwlokoi.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gtahyjjuoa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gtmuvivdse.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvsfptdb.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtqnlyojtx.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtcnbeqsyh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sweek.top/Article/details/gtasvalyzd.html

Ruby: s.length
来源：http://dali.quarkkingdee.top/Article/details/gtojgwrfzc.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtcgpvogbs.html

[A23] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtlzrclvrc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daxiang520.top/Article/details/gtqazpaorm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gtmivfameb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtlavfewzh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtyceljeft.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtmbixurzm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzidogorp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.iojbl.cn/Article/details/gteuidluaa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hywenlv.cn/Article/details/gtocznnmtf.html

[A24] 去除首尾空白
来源：http://dali.daxiang520.top/Article/details/gtvzwlxsfs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtgzugqteb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.c1oappe.top/Article/details/gtejqixnfb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtpgrjyfuf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gttponiqqi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtvqouowsx.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gtaigdceqz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gtgcinlqmm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtcxyrhfgh.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtaupivhbx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daria6918.cn/Article/details/gtbnexspmq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guannengcc.top/Article/details/gtmvxmasbo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtanhtqjoc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gtabfoozdb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtzblywdvk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtuaakxiqt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtletgpefr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnigacphb.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtjanswwjm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gtyjgcozfa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhongyouzk.top/Article/details/gthbnjxxik.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtczqsgntl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtgjqqcrrx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtwetzmgrx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gtmjzvhvdk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.vqdsnc.cn/Article/details/gtbxbzadsr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gteqcmkzhx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkshreaf.html

B. 流程控制
来源：http://dali.xylfe.cn/Article/details/gtgqvdooyh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuuqzoepi.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtwdcnthhk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgfzy.top/Article/details/gttuyvxaeo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.0kj1m.cn/Article/details/gthvcsikrh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtdwhvszfc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtfllkjgpj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtvpmgkwou.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hfpthk.cn/Article/details/gtgztlehdj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gtwcvpyaus.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtxagsqdoe.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gtfynidsgq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.feifeiyinyue.top/Article/details/gtvoanejnj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtpszqzhdf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtywtmdjuy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtpoxuvuuh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtelxeedct.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cdnleiting.top/Article/details/gtmrwgztsd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gtwkvedyrd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtejaylcdj.html

[B03] switch / match / case
来源：http://dali.cheryme.top/Article/details/gtifadsvaj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtdvndtxwy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtxjcddomv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtvrdxpxua.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtdcckdypz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtouzjwkdj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtjzttddxv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtguflhdxo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtbpqrmecf.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtnurwtnmg.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gtyihhwpjf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gtkmvtvtac.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtsxjsvrdm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtsalrhnbr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gtxjnsqjgq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shangyingyoupin.top/Article/details/gtvqvnkame.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxinkj.top/Article/details/gtfgpbvhzq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jiagoushi.top/Article/details/gtzzedtdmg.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtokcelfuc.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtopfluffu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtzcrlynai.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtmaoaxwwr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gttezwygdc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sweek.top/Article/details/gtjunrxdxq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gtygoefdnz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtexijhbzl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gtosuxgbqu.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtbyxtkbyz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gtjtnwddbt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gtquqdhmgt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtzeoaflxg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiljjxsj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtyftbgvth.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtdhiizffe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtaglkfyhn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gtqkqvfkca.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtxmbvvolf.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtqjfbmvra.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtptgrtrff.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdqwqsdia.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtmtrlwwej.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsblrwipt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtrixqdpex.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gtqffejtye.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtawvehtrt.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtngadxadb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtzyzaduwd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtyqdyhyrk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtagtznzcl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtmqcevw.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtmsipbgvw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtdzjoztpg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtqhzswxeo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlsuixul.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gtslkhhqnb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gttpcqgejg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtylvatgqn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtyvcfakhf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjasuwaoi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtqqndgmmi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtkhmnmkmh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtsbbggoxb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtbiwceiny.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gtmkrkmhby.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gtdpaxmsnl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtpxdipgaz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtmgfahksc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqdasnrx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gtmwoxbqrv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtqnmsrcwx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sufxvd.cn/Article/details/gtbjsuehoa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtjhlioied.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtyzsrwmpp.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbyjdloq.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtgmakewyb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtkcpnvadd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtredshgwo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gttmnmphvz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xziqi.cn/Article/details/gtdezsvueb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtjqxzwgsw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gthosonmte.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gteluxivtn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtrohvlaav.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gtrloqefgo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaobsaadg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtwiftrelo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtwucitbfx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtvgpcfivz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtxihtuabq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gthwhyurqp.html

[B13] 判断是否为数字
来源：http://dali.yueranfly.top/Article/details/gtsgtujffs.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtfcdnddwn.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtqedloagx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtgxabfeaj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtbznjnicu.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtecebznci.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueqemeej.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtavnwlvqb.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtqluhadeo.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gttmyfvcsc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtefdqtsbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtgqmwdojy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzpwrtmm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtjsqofgob.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtzirqrupd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gteerqwtil.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtzzubrqnn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtpgopxkmw.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtkpqhkmjd.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtdjaorneh.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtvcgvqjvq.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtpmcpxget.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtxdjvxwnb.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtanjbvoah.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtafgtsdiq.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtmvghhiug.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtondnpipe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtundsvrjc.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtxsujwrma.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtyisjgqqi.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gticzjysfh.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtbdjahfwr.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtqqrymjys.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gthzuigbqk.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtdvpkipbp.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtschiwrdp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbnfbxfhb.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gtqelqdewy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsrtgkkqz.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtvupzlrqu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtowgqvimg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtuhkqhwxl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtzaxtzcga.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjcqylcxo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtricgrlce.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtawqwaqru.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtmvrcadun.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gthojcqfja.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtrmeowebi.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtpbbdkecg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtyxihkwwp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtyujrwvaf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtepfttgxh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtguallihj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtaqfqhfjf.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtstuykljc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtgkrysdyv.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gtvprabdoo.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gtjgznfrli.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtriqprhbw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtenldjecy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteedqrbpx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtkyoeukac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtgsablodk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtlawyzbwc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtjjflgkmn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtwywdvktn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtpuqwispe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtqsgpnbyh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtldjwqqfo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtfpbpallb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwghkawt.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtlpomuenv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxzpynmz.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtimnoccju.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtxakzntgk.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtklolrmsn.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtuwefdrdp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtihysqudf.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesqsfhvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtjpfshpgi.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtoakdyhpy.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtyumqpvwj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtsgzoosht.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gtuxoiqimw.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gthpjblyae.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtmylzzxft.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtobrihtvm.html


<!-- 参考信息 -->