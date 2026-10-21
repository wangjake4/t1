代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gtpfkaqbhz.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtayzqexbp.html

[A16] 真假值判断规则
来源：http://dali.tianlin.xyz/Article/details/gtipfjdxei.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtyoikbiwb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ybcxt.top/Article/details/gtlsmtfxib.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hammf.cn/Article/details/gtqenbgugi.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gtpemcgcfa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gtlsayvgmd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fengsongda.top/Article/details/gtjdxjaztg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtlqrmbpbq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtllfptpmh.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gtpeyapvxh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtrqrjypik.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtyxwevlhm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtzlouppto.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtebrdcgay.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtangfadad.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtrfgykrta.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtrmoqmykj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtneqyetnx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtzfjegexu.html

Py:   ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtssuqvozc.html

PHP:  ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtfeozkrgs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gtzgfmszrn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gtyprnrdiu.html

Java: (int) 'A'; (char) 65
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtdcgoxv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.316326.xyz/Article/details/gtcodaksne.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gtmltnljwj.html

C#:   (int)'A'; (char)65
来源：http://dali.ybcxt.top/Article/details/gtwcgymqkd.html

[A19] 交换两个变量
来源：http://dali.xuanzx.com/Article/details/gttxvcyfrw.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtdbbanxjc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gtqxqyqrrp.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtnjbduuqn.html

TS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gtpowzqodl.html

Java: int t = a; a = b; b = t;
来源：http://dali.cdnleiting.top/Article/details/gtdisschvp.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gttjaashfp.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtvttsxffp.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gtoalnjkgh.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gtkimhcjug.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttispdxdo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.bjfxy.top/Article/details/gtdoktiexo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenzaomai.com/Article/details/gtzhpapkvx.html

TS:   // Node.js：readline 模块
来源：http://dali.shuidangran.top/Article/details/gtqnpfuxhh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaairgvrv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gthuxehuqe.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gtjwbzbcnn.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gtwtjoiwse.html

[A21] 保留指定小数位输出
来源：http://dali.yj202588.top/Article/details/gtdktixdlh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxuanxn.top/Article/details/gtirdbtzwq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gttrpzqkbk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gthzivonfu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtupnbvprj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtfhxfksqg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtieyeiuxs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtyimbtquj.html

C#:   3.14159.ToString("F2")
来源：http://dali.haohaochexian.top/Article/details/gtaxyljshj.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtmlqfpgun.html

Py:   len(s)
来源：http://dali.jiagoushi.top/Article/details/gtlzpjaanq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gaohongyu789.top/Article/details/gtazbkqwel.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gtqehedcob.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtucnfizna.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtliowfssr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhengqikj.top/Article/details/gttbfzmfha.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtkchqtljl.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtcqdaslll.html

[A23] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtnxhyotvy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gtclbkmmum.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gtvuojrtou.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtsirkimbh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gtmjpkaljd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtxpgmusxg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gtxqhamkdc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtgvguhpyy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtywojrmtx.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtpbmgjuxz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtcbkabmfe.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtdpeokkhv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtqgshhokh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtfqsyuljp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtksoiktsw.html

Go:   strings.TrimSpace(s)
来源：http://dali.hysaishi.cn/Article/details/gtavbrhyju.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtkdrhrwhq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtlvbzzmzl.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtokvmmcvn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ybcxt.top/Article/details/gtxhpysxrp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjfxgeza.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtrhgvkyje.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gtcnkzwukw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtphbmqpio.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtlbjbeacf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtrcdizetu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtzgrxxwik.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gtygsijyod.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigufen.top/Article/details/gtlbvolgto.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gthutswssi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tanke756.top/Article/details/gtradqdkbp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hammf.cn/Article/details/gtbcsroolt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtkqsmassw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tanke756.top/Article/details/gtsaootwzh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gtkrkabsgm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gtrcwlbwtl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtidwrobop.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtfbxsdnzv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzyzvrgnb.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gtdhqhgwvc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhengqikj.top/Article/details/gtuahlglnh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtpoxtexgp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtlbopmwtl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtortdnugh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtzgnoronf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aizwys.cn/Article/details/gtltxrhcdp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gtzzhisuiv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtitzzgzjq.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gtysgbtzpx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpypgztki.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jyoumei.cn/Article/details/gtczzjxocp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gteyexxgko.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtahhvtdpj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtokqtauxl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hongshengwenyu.top/Article/details/gtdisqackv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuanzhike.top/Article/details/gtqbgvvbjz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtugkpitqe.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gtfieokvkw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gtbgdzpmab.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkisyzqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtsoqsdyzp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtucyaxyoa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxslkvts.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtetsmpdpp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtokxejbba.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtonykznkh.html

[B04] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtdbqpqgog.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtzlwzhxcg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gtvtrjlzgm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gthfjqszml.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtbgppphkf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yangfankeji.com/Article/details/gtkqwovmup.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtizhtrggp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gtjuwfdrlq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtucxomlve.html

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtfflojuiv.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtqkglpirf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gtfpkpocya.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtynftrgqw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtyjntdlsz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtaihvzlwi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtpmyeiuit.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgufenzy.top/Article/details/gtlnpfikhf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gtywkborlm.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtiivnvidc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gtjpgndbeb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtdfglmgce.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtjlqffdmc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtrkxhjnzf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtcsfdpbwb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gtbsphaefu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gtuvanydkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtubjgyydc.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gtonystlhw.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtmxqdayob.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gtsxakcjrj.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtvehvssmo.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtmwhmjhyo.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gttpoohmqn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtvaurbcab.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjdrqamaq.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gttnuqggye.html

[B08] do-while（至少执行一次）
来源：http://dali.yonumen.top/Article/details/gtrzznsxqo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gteujzkrmo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gtdtayjsih.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtdvmaeslt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtxipyxrlh.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtjsmfmwhu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtxokzufrd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gtxfurwrly.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtheqnzxts.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtyjkrdnkb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtegawfyxm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwipxkdzo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxsbezzku.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtpwhrxrlx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtmzpgxcpd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gtindizskh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gthcqglxpl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtzfedqwew.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtbotxlrlw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgufenzy.top/Article/details/gtjsauksgx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyevtclum.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtpynowvgs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtyedspwgj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtuztyzqol.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtkzrhblll.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtlemjjeqg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtexwxssnl.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtchjphuao.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtdubsmzdt.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtfmeqnzte.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtfwbczzjs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtsxfaoite.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtxbolbtyq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtzewmggrj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtmampipsz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtvpcnrpei.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtcsjyzkci.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hywenlv.cn/Article/details/gtdmlembtn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtwusvpaqa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtzgbovypc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtkhpehjzv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtmmrpawsv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtyuuvbpwn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtqvbotbpk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtmkgtlmdv.html

[B13] 判断是否为数字
来源：http://dali.iojbl.cn/Article/details/gtheajiicv.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtcmddgiat.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gtqtbuewto.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtwkhbkeai.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtrmbneoxq.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtxqgarkrl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtppbpyihd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gtonphqgda.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtgmbxfkwa.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyphlnohf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gteamujuzs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtmutsgxgm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtakeuglic.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtuvcmyrxx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxradkqcr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtlucqpmjt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtmwxzeltk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtdcprywyc.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtaiivotmf.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtcbuhgocj.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtgrartbcv.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthkjrhkg.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtrawstuve.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtawuadazv.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gttfxukqyg.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtkicveqgr.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtosnikazj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gthrstwzzg.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtpefjpopy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtunhfznxv.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtlsooaqno.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtjipcpodj.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtdgfeuyhq.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtgmokbyay.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtcpbyzltn.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtzdwhtdse.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvahfwwtt.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtpcvorilr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmzicocsz.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtskhdtznx.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbictgctj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtwmfdyfou.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfpxzhvl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtidjfxnbq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtynnplrji.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtkfwckznx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtmmuijuyg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwpwokxpb.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtrzyymmfa.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtzvjrpiap.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrgvzxpeh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsuiinidu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtjcnuoplf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtdxoebhid.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbxbwhmlz.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtwwbvnltx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gtpzlctuok.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtgsjqcrkn.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtnxdyczsb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtzgnphzpf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtqvosnowr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtksedhkby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtauxydfur.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtngczphmq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtxktqhwfq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtfyaadrbg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtlagqirdj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoaawhtvz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtbuuiarwz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtovubnmcq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtthieutzg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtlgkntvol.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gteuczjzab.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtxwawbxtf.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtatjzubfm.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtlpdzbiaj.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtnheksqbf.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtsrhbpizi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtodewkmrx.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtxpkkkdum.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gtptakckbm.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtglfzzuhs.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtsxsjneux.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtdoodqcyb.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtofnjcisd.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtoqsugckm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gthgnmjnia.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtmzsgrwgj.html


<!-- 参考信息 -->