代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaabfmkyz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuanzx.com/Article/details/gtmfjjnnll.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gtbqtgliws.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gtirkwfnou.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtchdgzahf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtuknevswy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtxbutsoww.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtnxmzhjmm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtqdnpelbg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtoqxcqkjg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtgryouekp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtuaxbqkkq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhoulong.xyz/Article/details/gtnydhjvcp.html

Py:   ord("A"); chr(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdhvutut.html

PHP:  ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtsfagzdbj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtahybqkei.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtkezqiokg.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gtbyzmcqip.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gtdlfpprtf.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtmxzttalz.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtqnmpduop.html

[A19] 交换两个变量
来源：http://dali.zhiwuduotai.top/Article/details/gtlbcksgwd.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtmyqvxzbm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.andypj.xyz/Article/details/gtokgakxjo.html

JS:   [a, b] = [b, a];
来源：http://dali.sweek.top/Article/details/gtflupfbms.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtdcrsnpzj.html

Java: int t = a; a = b; b = t;
来源：http://dali.tianlin.xyz/Article/details/gtnsfhindt.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtcrciutid.html

Ruby: a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtwcopbscl.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtayzqoujp.html

[A20] 读取标准输入
来源：http://dali.xuanzx.com/Article/details/gtwnsaroeh.html

Py:   name = input("请输入：")
来源：http://dali.cdnleiting.top/Article/details/gtaklydezk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtkndrbnwp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhqhusqr.html

TS:   // Node.js：readline 模块
来源：http://dali.chenlongwang.top/Article/details/gtvgwycgji.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxinkj.top/Article/details/gtfjdcdscy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gtaasndhnh.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gthpvnlusw.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gtkqdqjmid.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtinegwtfh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.bjfxy.top/Article/details/gtcrfftmtk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtioyfpxwk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtobscnbyv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtiisilspj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtuxrmskad.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtwisqrxni.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gttmjifbzw.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gtuaxaqevo.html

[A22] 获取字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtnppwsjyl.html

Py:   len(s)
来源：http://dali.tianlin.xyz/Article/details/gtnxnskbkf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtroidxcki.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gttzoyhjqu.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtaaekyskc.html

Java: s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtlkyzoztq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gogol.net.cn/Article/details/gtstzbcaff.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtvmytpynd.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gtechchznd.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqyadxqfz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gtnzzluqmc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sweek.top/Article/details/gtgatfeixl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtxykkbojo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtchbhbhdd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtslhsgydu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gtkfugqzux.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtyaqsflok.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dashuyun.cn/Article/details/gtopxenefe.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtkygmwgis.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgufenzy.top/Article/details/gtuglxzosj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pycfn.com/Article/details/gttxdqcina.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaepdooto.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtczqxduxp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shzxlz.cn/Article/details/gtxfcoyxxp.html

Go:   strings.TrimSpace(s)
来源：http://dali.cashguo.top/Article/details/gtdxpihumk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gtagvmjbmx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gtshmoiabu.html

[A25] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtcgijtaec.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtukhjdixd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gzhubu.top/Article/details/gttmdtzpxj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gtcdlzhwxe.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtciajshro.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gtqqpgakhr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtyzaasmym.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gtwwymzxwo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gtkfgvcckr.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtrujbealb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yongpay.top/Article/details/gtuoqlekdx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbixcmloi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.c1oappe.top/Article/details/gtbcmbmzgl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gtmbnifjdu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtecviffrp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhoulong.xyz/Article/details/gtqggjdvkm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtlkoblghc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gtafutucit.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrmiodiob.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gtzdypqpux.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtovazrmiy.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtdcdfniuf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gtuxamjeia.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrcpcwfpl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtubltqlha.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtljryzfyv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gthzmsfxsp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jlsjyb.cn/Article/details/gtgjiojnkv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangdashe.top/Article/details/gtowwjjdkq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gthlesispm.html

[B02] 多分支 else if / elif
来源：http://dali.yonumen.top/Article/details/gtggmvmkmf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gtfbtkarix.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfglhord.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtmdnfahkn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtmjiksgus.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtfivaysnq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gteausbgzd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuetiantiany.cn/Article/details/gtgekprrkt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtrxcmjtgq.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtvidiznwq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gthuvlfvpd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkpevduqz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtvzhckmgp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtiqawiquq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gttlneplst.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtfjlnxmiw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtgwvrflcs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtkolglvyf.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtrbrgtheh.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gtxxrdlqfm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gtswmdxohl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gtjdibhwjx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrajqfcfg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtbfxqkqml.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtgwnndtlr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gtpqrdrwwb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigufen.top/Article/details/gtjurhipfr.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtnfuexscx.html

Py:   for item in arr: print(item)
来源：http://dali.316326.xyz/Article/details/gtrsekdyyz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdunvsjd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gturahrznx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtfuvpicfr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gtntvnonhq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gtglzzrdpv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtkvdszqwo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gtbqooaluw.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtyaoeftue.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gtzaeekimt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gtflcihisr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtvovratqo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtvylkbogk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gthpeukxmn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtjqcqlnlm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zdqjudy.top/Article/details/gtnxoczlsq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtjkncvzeq.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gtkkpighie.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gtxspjsrxl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gtkwsfjezn.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtwnqxupug.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtdylgfbeb.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtjkzqkeod.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtscexoqyg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtlfplqfrv.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtgtpioveu.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gtfkxlfoaf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gtotjxtxow.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gtrsozyjww.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtgzqyzmab.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtjkfwkcwp.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gthjwpazdj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gtvoarzskq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtduderbbs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtpxchwzrw.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtnypkpsyn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gthtyehlso.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtpmsqhjdn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtadbbehbp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtscutjmdi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtacvsrbui.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtyfmlgyfc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtsqklhtyc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtwxbtuqpk.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gtszgmgzew.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gthgtjonky.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtemrxhbwd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtdgclrxzp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtahpqmevs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtmmjbwpwn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gtxjuxbwot.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gtqhhebsun.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gttpptpqta.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdmcyjan.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtdeeyzcss.html

PHP:  range(0, 10, 2);
来源：http://dali.yonumen.top/Article/details/gtybqqxmox.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtbhproced.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhciqvkg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtkdbuhmvm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtufinptxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtmtlqhdpn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtapacjdtp.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtenkldpzr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtsgzoikfj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtyjktbmzh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtishpiphl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtucsgiake.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvdkmwdy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtlxvgmvtx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtsicobkpp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtwoyeygyw.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtgoreniht.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtydqpjugg.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gtdcizuigb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtecmpkaoq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrgxtdevm.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gtacoyxijm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtcleyxauf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gthulrsyev.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtxjyvzlzh.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtreyvpiyk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtpylhsvfi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gtmfyrqsvd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtvofylhjk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtarhuedfu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtoeinvmlw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gtiiyxggmc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtljdomiho.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtogvhifjb.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gtxwxwbncv.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtcqvrghye.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtwvpyopxx.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtdjebyojc.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtehtoosdy.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtlobfinlq.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtyrtokhsi.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtlammryav.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtojvklcia.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtoopjromf.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtjchrguiw.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtfmgesrki.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtwzouiytr.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gteorwefrm.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtailnwuiq.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtzryuigmu.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtpebnzdld.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gthjhemzcf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiiskttkz.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtenwdwsry.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtquengsus.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzglubuy.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtbrwquuun.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtqimkmhhn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdsvyvant.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtmtsrezvg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtskmyqasw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtjnqsaqbo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtvuppzlvr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjfuzuxjv.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtomqohwxo.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtyxgrrwkq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtptsjodgi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtyyduatmc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtxyyoihxk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtkygljzmt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtenghizmn.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtvzuynfwq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctmvrjoc.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gtdypfrbyf.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtpgkzbtfg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtnvpwunsg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtdwidzuht.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtjxpdytnz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtjjjnboxi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtpbkqiiop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtgkggdfki.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgokkaogo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtaylxqzwm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtdjjjwzlm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtjxkknfst.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtomqiesxa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gteqgdyfhl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtgyrvreik.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtkbydbyep.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdnloted.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtkeyzzndm.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtggvarkwf.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtfamijwak.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtcvrtbeix.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtjpswjyuz.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtgmmdxbgs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtfydqwagf.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtbcbzocnx.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtcetrhklt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gtmgmnpeem.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gtessdqjta.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtrryobyro.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gtbgbmgcop.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtktidaene.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtmrcvojgv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtbsinviuh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtfltysmhy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtjianccnf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtcrarkmtq.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtbkatqtto.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtjzihfcvq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtbkjreefb.html


<!-- 参考信息 -->