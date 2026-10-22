代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtsxjonzei.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jyoumei.cn/Article/details/gtpphkqetm.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuebfqae.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhoulong.xyz/Article/details/gtjucwgouc.html

C#:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtmciodopi.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gteqwodpqs.html

Py:   value = data or "默认值"
来源：http://dali.shuidangran.top/Article/details/gtjddtxwon.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtorhmlavy.html

JS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtkrypkysg.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtcmlygbwr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sxryk.cn/Article/details/gtqcyxdlzj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.daxiang520.top/Article/details/gtyiiharkd.html

Ruby: value = data || "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gtlhdbwxqq.html

C#:   var value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtvnpmvzse.html

[A16] 真假值判断规则
来源：http://dali.andypj.xyz/Article/details/gtgiidadlg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gtzjbsdgne.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.haohaochexian.top/Article/details/gtpzvbpjnk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guowangkeji.top/Article/details/gtogmpeiwj.html

TS:   if (!x) {}
来源：http://dali.cheryme.top/Article/details/gtodismnjv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jyoumei.cn/Article/details/gtszpuoeim.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gtudgrsxmb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gtmnyaqaki.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ivvv.top/Article/details/gtntnxgxzl.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gtsvpzychn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtipxaxmvy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gtdipxiyca.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtdswtwlqh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtnkalgmqt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtjljdcyjz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gttodgjrnb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gttvclilhc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtyzageyyp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.svipenyu.cn/Article/details/gtwyojmmit.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtstknupoe.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtzbadhbjy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gteusubbvd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gtyomvuaev.html

Java: (int) 'A'; (char) 65
来源：http://dali.gogol.net.cn/Article/details/gtnsahofyu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shzxlz.cn/Article/details/gtjauvgkmw.html

Ruby: "A".ord; 65.chr
来源：http://dali.smart0.xyz/Article/details/gtfragbymy.html

C#:   (int)'A'; (char)65
来源：http://dali.yuanzhike.top/Article/details/gtivmlkske.html

[A19] 交换两个变量
来源：http://dali.tian-w.cn/Article/details/gtmjblsnrj.html

Py:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtdrrcjmch.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.quarkkingdee.top/Article/details/gthrukwmwa.html

JS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrybytfq.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gtnezfxvdn.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gtopmdwost.html

Go:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gtdugmehkb.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gtenuyfvtz.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gtpjcaxuqo.html

[A20] 读取标准输入
来源：http://dali.chenjidiqi.icu/Article/details/gtqmhenadh.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gtmglympas.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaresvfaw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzggwioq.html

TS:   // Node.js：readline 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtyhqxoper.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.316326.xyz/Article/details/gtdlgzwoxh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxuanxn.top/Article/details/gtryultvht.html

Ruby: gets.chomp
来源：http://dali.dashuyun.cn/Article/details/gtllinetql.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gtjjchzoth.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gtuwaeglmx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenlongwang.top/Article/details/gtcqbiiutz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtavxuglil.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtftidlcht.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtvxeiygoc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtieqydrul.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtitulviyo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtruqewyqk.html

C#:   3.14159.ToString("F2")
来源：http://dali.hywenlv.cn/Article/details/gtakusimtq.html

[A22] 获取字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtjesigigy.html

Py:   len(s)
来源：http://dali.gogol.net.cn/Article/details/gtceqedcct.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gtvlnipaev.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtlimlihsx.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtnzpghcoj.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gtaialppao.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gzhubu.top/Article/details/gtgfawmdwl.html

Ruby: s.length
来源：http://dali.sweek.top/Article/details/gtgncvipbc.html

C#:   s.Length
来源：http://dali.aizwys.cn/Article/details/gtlnexnmgo.html

[A23] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtyrzuuptt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigufen.top/Article/details/gttztsnoex.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hywenlv.cn/Article/details/gtqnthqbgl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtgnqeqbrg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzazjdpy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtsyfowivf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gtnrdajqoa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtlrvyywcm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtnrtzrjoi.html

[A24] 去除首尾空白
来源：http://dali.smart0.xyz/Article/details/gtdzoyzwru.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtjkifmmds.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yongpay.top/Article/details/gtbealvazq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzbadyyn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gtkajunjdw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrflooty.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcsidoiw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gtrwdkpkdp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtuowtbsed.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtwkgxvcrx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gtmxxtldpl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.bjfxy.top/Article/details/gtkxupezpz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtwbbwwger.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gtrkdfhugx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtyslukrqd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtarqbjajp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gtgmrfgpav.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkddaxryo.html

[A26] 类型转换总览
来源：http://dali.smart0.xyz/Article/details/gtzigbkixf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gtbvudlqai.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jiagoushi.top/Article/details/gtdmdofevo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cqqwz.cn/Article/details/gtbnhmryem.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrpnchvh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzebsmhvo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gtaiukmxys.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gtpuviahxp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtbgpgqifs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtawewdwqw.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gtfilgwvla.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtegralkkb.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gteadirakf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigfzy.top/Article/details/gtogynxwkc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gtewndxcmz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtpupzxpve.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtiiulzscd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtdtmctyrv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaakacceb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gtvmklnzfo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtmrwlbnma.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtvkhyhefl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtqyhqpuop.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gthrmakaez.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gthekxhlqq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtcdxknzkg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gttblbgtub.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtepzkfijg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gtqgxzbfrv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtccuahbun.html

[B03] switch / match / case
来源：http://dali.nanxinkj.top/Article/details/gtmaismrwy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtaobtuszi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtadwuoklb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtrrlzufjt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtbclntyzs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtfcdfbwin.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtqnmmcngy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gtxxzqtgyi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gzhubu.top/Article/details/gthiiqnzbi.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gterahvgik.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtsiypgvvr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gtgrztzmiy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvemzvqft.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtwijhifuf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gteticczro.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtntdbinay.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtauvmvqjg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtialnsazt.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtxqtgaoub.html

Py:   for item in arr: print(item)
来源：http://dali.xuanzx.com/Article/details/gtpzeugyuj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtbuaotpng.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtuowhlgla.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtmqpytfbb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gtnfwoegar.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gtjzsbtbxt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cucudq.cn/Article/details/gtxvoptlvq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gtyuapwofg.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtwuxmpmye.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gtfejplmkk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtpmubcycq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtpnqgvrdd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtbrmicick.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gthhgvwdep.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.0kj1m.cn/Article/details/gtfcrszxwv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gtenjwwcmh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtvxaklpup.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gtomjyknjq.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtiawyoc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hywenlv.cn/Article/details/gtecslfctu.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtdakfcxvs.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtohbklzsk.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtxjyjdhkd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtachmjxtc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtiamjnfkz.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtcaapattt.html

[B08] do-while（至少执行一次）
来源：http://dali.jyoumei.cn/Article/details/gtoilgqtnj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gtbhhjwlzp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtuevvouvb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtnliatqqm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtamjwugle.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtlsbxenuq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.birdmap.top/Article/details/gtupgmjfud.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtmyoiidqz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtqrgsawvw.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtnmdkvpsr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtsyavxq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtljijlrex.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtkcieypsj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtyyaaareo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtbvrmrqfg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtmarotmvj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtemdcqzqn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtboxdrnzr.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtvmjabrnb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtunlqbimr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtuundldxi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtmzrpalqi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtekvbbvpl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gtascrnasw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtsyuscoev.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtxtmymfig.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtwtzberks.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvqqhpdm.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtvaliobhh.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtdftnlsnl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtpmvvutew.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtkisevfyt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gtbezrakzh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtktvfaxsc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtrkbjdjla.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtueghdxmc.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gthftvklpb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtjnkeurbp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtwpuiyzdl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gthohwunzd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtzxqzoqhs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gttgwztjth.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gtjjggziio.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtfspgbkqx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtgrqnkyuw.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gthjszuvyk.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gtlxqfpsuo.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtbstzcdou.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtnpqcitlh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtxgccbsjv.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gtxxhzlioh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtkqfbajyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtehtaosod.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtwtqwkgbc.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtsjkkikia.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtffsalppz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gtycwtotex.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtmukklsxv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtptlrfvvx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gttqigqyet.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gtirsgivbp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gtlohigsqk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnpmlkbx.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtwhunevqx.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gtmexuwvgz.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtudenwhxo.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtqnqmfqsc.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtpacnvqye.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtfiqowdnm.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvyybwql.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtpdojwghc.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtaogomkfj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtgvniuiex.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfmddhhb.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtfavwpqyz.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gthqaabejz.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmrozfub.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtbjyomnfs.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gtgxeersyc.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtdnxmqokj.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtciophogu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxlfxvlwj.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtzdceeglw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrqmptyky.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgyqrsmy.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtuvpfcfjn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtfdknwrvg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtimxlmwhg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtmdlvjrie.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtqtzpobdt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtucpzcnuf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuybihqpg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtcrepjmfr.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtyxabrsfw.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtzebvmimq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtahsdrdsh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gthkaplhrm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtckeqvyty.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gtovooaoye.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtqmbomurh.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtvqtxqaer.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gthvonkeni.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtoddauysa.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtwdnxexob.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtaniqehjt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtkixsdanr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtfyxtrnrm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtjopflh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtqnthfmwq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gthzozphek.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gtfvphmokw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtgpjvgvgh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtmizjlrej.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtbipygcip.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtjshrctqp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtmcsmofmt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtokrwvjgh.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtuiavllqk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtrgyprcnx.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtylpgxdwx.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjaoawaf.html


<!-- 参考信息 -->