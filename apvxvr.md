代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jlsjyb.cn/Article/details/gtuarcfgwf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gtmigpkgvt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtgnkhkbmp.html

[A17] 位运算
来源：http://dali.smart0.xyz/Article/details/gtozpqwvbj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtdonbfcie.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.birdmap.top/Article/details/gtiyeoqlwt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtulonepxo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtijbtbjtw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtfqhlkcbn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtqhikfdlm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtniujsvfu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtfofssxpp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pengpengdd.cyou/Article/details/gtpifaflka.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gtdhboaezm.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowyoaiac.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gtxsmlcpoo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gtsijekjob.html

Java: (int) 'A'; (char) 65
来源：http://dali.hammf.cn/Article/details/gtjzlnaoco.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yanxiufei.cn/Article/details/gtthufoihh.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gtffsyqqcn.html

C#:   (int)'A'; (char)65
来源：http://dali.yangfankeji.com/Article/details/gtsvwleyos.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gtboykqilt.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtfahdcmtq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhengqikj.top/Article/details/gtmxnmbqjx.html

JS:   [a, b] = [b, a];
来源：http://dali.daria6918.cn/Article/details/gtsufjoivk.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtrgydbfqi.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtqbyowkxs.html

Go:   a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjvzkjni.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gtnjqmidtr.html

C#:   (a, b) = (b, a);
来源：http://dali.ehwqpu.com/Article/details/gtheblutuw.html

[A20] 读取标准输入
来源：http://dali.daria6918.cn/Article/details/gthumpmstx.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gtshzobkcp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhengqikj.top/Article/details/gtngdntgpb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gtvonhawdi.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gtvqpzutci.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtvupxmsss.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guannengcc.top/Article/details/gtltuuanph.html

Ruby: gets.chomp
来源：http://dali.andypj.xyz/Article/details/gteupwfqyu.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gtphjjsbat.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gtlzikhwiq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yueranfly.top/Article/details/gtrzxbvzfz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtnhzgjabh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtscozlxhv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtucazrblh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtwutmjqtt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtyptjlvmn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtojkfdedm.html

C#:   3.14159.ToString("F2")
来源：http://dali.9152youxi.cn/Article/details/gtrknjkjqp.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtesizfpuy.html

Py:   len(s)
来源：http://dali.0kj1m.cn/Article/details/gtvzkehats.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gtzogepjmz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.9152youxi.cn/Article/details/gtyeauypjj.html

TS:   s.length
来源：http://dali.yvedp.cn/Article/details/gtolsfaffw.html

Java: s.length()
来源：http://dali.hammf.cn/Article/details/gtaqlsvgue.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gtfmufifvk.html

Ruby: s.length
来源：http://dali.gaohongyu789.top/Article/details/gtlyfhxflt.html

C#:   s.Length
来源：http://dali.wangdashe.top/Article/details/gtqacfdgke.html

[A23] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtagfatjnr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ivvv.top/Article/details/gtffeevizx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gtvfqtffhp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gthydjctvf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtsiktrdiy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfvycptg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.316326.xyz/Article/details/gtoilenkiu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gteengdjtu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gtzkutgxal.html

[A24] 去除首尾空白
来源：http://dali.shuidangran.top/Article/details/gtzgqadyxv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cucudq.cn/Article/details/gtbtmovdep.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtzmsafzey.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtizapcysx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtpiifygtz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnqzz.top/Article/details/gtwmfsyedc.html

Go:   strings.TrimSpace(s)
来源：http://dali.snrcjt.cn/Article/details/gtbhfcnbax.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gtqbijyptn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtcnlddapx.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtpmveeawy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.redwolf501.top/Article/details/gtqffigmgm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gzhubu.top/Article/details/gtgvwqohzg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gttkyangaq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gtvtzqftuh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtvayicryr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtntxqwrbr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtirudecog.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtnscchblx.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtilpyyhea.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.snrcjt.cn/Article/details/gtrfboyvjx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gtsqutxawp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtvaekxofl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtzkmofdzx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtdblilpfx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtleffrodw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtqnlbjgeg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtgrmyuusp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfzgnkera.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtfwhjqhtf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtskrpagoq.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gtshahpocj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hfpthk.cn/Article/details/gtysosckng.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqneklkh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtuoeoxjmi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtrhcqaghb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtgsrsjxzu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtohwjjtdt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtzihsryqp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtpwzbupua.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtmvngtabh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtkuexuqjg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gteczuzfzt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtnxspuonc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtnssuwcyh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtvjcbiyur.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gtlajpbghb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttylcdjck.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtqjkxlkuf.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gtbtuynupm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtldmvjayp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtdqymdcqg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrrauqqza.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtsxzixgre.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtgwxtilot.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtwlsihdup.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gtytlojtvy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtsiglflwa.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtlrgzgcde.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtsuxupeqq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.iojbl.cn/Article/details/gtmtadxpvg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvesfoujc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtsavvacao.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtqtgvcfat.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.vqdsnc.cn/Article/details/gtuuquurzo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gtzmiiavey.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jiagoushi.top/Article/details/gtpcscdicz.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtpkzrhoum.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gtmczddwxm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenjidiqi.icu/Article/details/gthiuxstki.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtgomikxcf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtqyqjxehj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtszswlvwz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gtbeitrswp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtgamzswtc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtibvdrrky.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjspfxwr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gtbmvjezap.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzirfrnzw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtixknzljm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gteievammg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtgkoehhvf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtlqyxilqj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gttzdlynra.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtfzvkfsxw.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gtrsijyqqy.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtawohbtkt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gtewxtarzb.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtoztvicbo.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuzsgpyjv.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gthikjysla.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcnsryfm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtdtfrqsuy.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtmggieoxc.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtxvdibwrx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtyogbvoob.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtcmoxyqti.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtquqrrote.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtddmrmojt.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtwrvbwhrg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gttkwcgxvn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtbxavxfbr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtajlgbgvy.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gtuhmjwqnj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gttwvmaxih.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtauimswun.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtazavrser.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtwmzdagng.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqocniir.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtjergyuoc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtpebkfwtf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtkvhoqnjf.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gtkzplyqww.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtpjotuagr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttmxgfofx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtxdjokypt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtxunhmypw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gteebgkzkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtdfhfyjhq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gttayfserl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtlahgpzni.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtwtxfpzpt.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gttvnukzcy.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gtfvhkehuq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gttjyufszw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtojlbqvev.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtyjxwghqo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtvxmflaro.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtysdnkyzl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtcedrswwc.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoiqecur.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtwkwbiwzz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtsiunlmhd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtjzojnvos.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtpvhapcto.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtozuzewhq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdppbfba.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtyoamjhnj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gtzslmhdwm.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtxgueovvh.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gthlgcomlh.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gttlkedwwd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsamaddd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtyianwrby.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtvycqgcaa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtgtfgtlin.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtjasohhhx.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gtwyydpxwl.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gtwtujgsag.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gtgsaobdqm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtftnfsbob.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthhdlodup.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtitcnrkno.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtaxofuhuq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gttqmimhrs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtnfmdfkvs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtrarjlbdj.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtmqayoxiy.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gttsmspndb.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezjxmodq.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtjiwwwvys.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtzbowrxnc.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtxjfbiafy.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozzyinab.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtrfxzecqf.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtasjkazrs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtlpraifsd.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtpneehhmh.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtnmxqhesl.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gteatxqqrq.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtsudvwdmf.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtjercrmqu.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gtbfwzocrt.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtqfcfgame.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtsrckwedr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjyiffeqc.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtolbltqsi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthspgkafg.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtxpyttiqs.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtcwggtcrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtdivrocvc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtoofbjuig.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtqsarodaq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkfpyhgn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtmcyiqpoy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtjtqnutin.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtqouavgyh.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtqtsaxrjw.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtdvibiwvv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtknvtiyiv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtisdlnebg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtxtoboqvw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtmdymcjqr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gturktjslj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtdtkzqytm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gticykkswt.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtcdvjraag.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtatmjtnxh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtwhyzkbhg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtjajkgalw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtdkigbfls.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtorrxcyuz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtjymfgniz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtoxhgnixe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyvuepfn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtxcosuhtp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnteitbpf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gtiylrhtqu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeflrefv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtlypsuvuc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwinmney.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtdiwkhhsc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtmiolqiea.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gteirbiznz.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtpbsjpcni.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtfocfrsxn.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtklbwange.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtofcsgcad.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtijejxuqz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtitcgvjeq.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtlscqcpfn.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gttajjlexm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtvteorgjv.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gtxrzzzcji.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtspmfznzx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtvkbcfrga.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtgslbguzf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtfqxtpgiu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtsanubwbe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtcfazxlhm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtuptxwtan.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtlpbiywro.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtrwmuiaow.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gthrivtufl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gthxykynrm.html


<!-- 参考信息 -->