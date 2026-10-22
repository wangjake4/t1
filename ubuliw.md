代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gtgpuzumxu.html

Ruby: "Hello, #{name}!"
来源：http://dali.aizwys.cn/Article/details/gtwwteucdf.html

C#:   $"Hello, {name}!"
来源：http://dali.9152youxi.cn/Article/details/gtlsdesakt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gtdwxwuoce.html

Py:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtgjikpubj.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtvdtdpttu.html

JS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtkpllaiwt.html

TS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtytboseut.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepkexhtk.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtmhwpxuiq.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtotqkybdo.html

C#:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtkjyufrmp.html

[A14] 注释写法
来源：http://dali.dianchejie.cn/Article/details/gtdbuyyzcj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.iojbl.cn/Article/details/gtgcrnisss.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtjirgfkxo.html

JS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtwonvueva.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtfqsreytg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yonumen.top/Article/details/gtntbyfrrn.html

Go:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtowlatrad.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ivvv.top/Article/details/gtmtiqhxxj.html

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtzcszrcga.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gtsnvvvqpc.html

Py:   value = data or "默认值"
来源：http://dali.ehwqpu.com/Article/details/gthbqomjgj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxufczmpg.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtrkxdipeb.html

TS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gttsazpvzi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yueranfly.top/Article/details/gtoqwffhco.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.smart0.xyz/Article/details/gtknjwglbb.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258.top/Article/details/gtltzyexsv.html

C#:   var value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtczaobziz.html

[A16] 真假值判断规则
来源：http://dali.chenjidiqi.icu/Article/details/gtnyquneyc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtucyatgam.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.andypj.xyz/Article/details/gtjjycgwek.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gtshdmuyec.html

TS:   if (!x) {}
来源：http://dali.gaohongyu789.top/Article/details/gtyiafpavg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shuidangran.top/Article/details/gtocvoerwt.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gtcyqarogt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtqgfyqlyg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gteyvqspgb.html

[A17] 位运算
来源：http://dali.yuanzhike.top/Article/details/gtleyexeov.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtzlknicrb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdycuwik.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtpmlvwfwz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtbfpshslh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtagwkowfj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtrhtuspnh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtbwnkysrn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtssidlpae.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yangfankeji.com/Article/details/gthdumxtkl.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwnuozba.html

PHP:  ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtkrdnnhdl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtsnsjjrcr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtpgulbjkc.html

Java: (int) 'A'; (char) 65
来源：http://dali.fzhhl.top/Article/details/gtnllwalls.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jianghu66.top/Article/details/gtujawylil.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gtjacmyota.html

C#:   (int)'A'; (char)65
来源：http://dali.cdnleiting.top/Article/details/gtijaynufl.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gtleeficyu.html

Py:   a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtoedlailj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gtqmnrgknp.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtivikuprn.html

TS:   [a, b] = [b, a];
来源：http://dali.birdmap.top/Article/details/gtijsdmukh.html

Java: int t = a; a = b; b = t;
来源：http://dali.ppjwa.cn/Article/details/gtmjokswcc.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtycizssro.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtqkrrpzwy.html

C#:   (a, b) = (b, a);
来源：http://dali.yuanzhike.top/Article/details/gttadfeubn.html

[A20] 读取标准输入
来源：http://dali.aibaodan.cn/Article/details/gtffzyrdwk.html

Py:   name = input("请输入：")
来源：http://dali.xinyue.icu/Article/details/gtpifbtwqf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxhykxfj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gtfnyguqca.html

TS:   // Node.js：readline 模块
来源：http://dali.birdmap.top/Article/details/gtshrdixso.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gtntbywwpf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthykzchtl.html

Ruby: gets.chomp
来源：http://dali.fengsongda.top/Article/details/gtfpaaatbl.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gtxmgriscc.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gteriifgmp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.quarkkingdee.top/Article/details/gtsiyxqesg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtxunhsaqn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtwjswoblo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtnzgenshx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtzjqzwsmc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrimlxyd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtsuksjfjm.html

C#:   3.14159.ToString("F2")
来源：http://dali.pycfn.com/Article/details/gtgvmjzren.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtiemjkdgz.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gtnsufazqr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gtbifpvlvh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gttsqzpfjc.html

TS:   s.length
来源：http://dali.hammf.cn/Article/details/gtpwzzeyzm.html

Java: s.length()
来源：http://dali.birdmap.top/Article/details/gtbgfgqqij.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gtowcvkinz.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtyrwqvbnv.html

C#:   s.Length
来源：http://dali.haohaochexian.top/Article/details/gthiitjejz.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtfcszhaqz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gtrrfvdxlr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigfzy.top/Article/details/gtprkckzuz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtykhpptmk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtykcyndfe.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtvxhhmlrf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gtrzurmpdl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gtelczdfai.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gtfhoavndx.html

[A24] 去除首尾空白
来源：http://dali.guannengcc.top/Article/details/gteqtupldt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.daxiang520.top/Article/details/gthyshnlji.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtzdgrtkry.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtepzrwtez.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zdqjudy.top/Article/details/gtosruyjka.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gticskqonv.html

Go:   strings.TrimSpace(s)
来源：http://dali.bjfxy.top/Article/details/gtqftllgjk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyrghaex.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gtmupjwqvc.html

[A25] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtcfbqodke.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtbqfiqyig.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gthjlcnmcg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfffqgmlo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtqovptyzk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gtuttootrv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtdiadyton.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gttdgyewad.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtvmcbowiu.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtcskxqdbu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gtaeakbqvh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gttbbeevgj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtjhtfjaqn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gtapdyzrnn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gtuzvxswho.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gtdwspselg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gtkuxvrmsy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtnyxnofim.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxbqwosqd.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtsuwegrlo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvjdposln.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gtqbqtzrer.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dianchejie.cn/Article/details/gtkvfhkink.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gtkoyfwada.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtlhfvcthp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtlzcmigys.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtkyytrril.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcukdjnlo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvhodfza.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtfgolsylt.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtauhnvygq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gtqipwspdu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gtlqnbxmla.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtcwrzetph.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtntzylgsy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gthjapgbvi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gtvprkcvyh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtzieshszn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtphsvfpqf.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gtneosxzux.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtiergctzu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtgxfwodox.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtxcazjavi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtwbspltay.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtrymnwygc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtxxtgvkhd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.birdmap.top/Article/details/gtpplbgxhe.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gttmqlibxp.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtddlqhnlg.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gthztdmmcz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtcapzchka.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtidafiauz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtyizggogu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tianlin.xyz/Article/details/gtnzsopely.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gtammewwpf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gtcziuswoo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtfmneytwi.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtepwzhdim.html

Py:   for item in arr: print(item)
来源：http://dali.smart0.xyz/Article/details/gthgcsnvvm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtizxgehhh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtoomvdqjz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gttugesxfj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamcgdkiq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtfgxzvdou.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gticlnhlob.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gtjiulgzqq.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtojnenngw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtaauobvpz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzoczbtgn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtwwccoxkd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtidksdgmw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtauixjzqm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shangyingyoupin.top/Article/details/gtjjbupvlu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gttzlvpqdx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtnsxpkkkt.html

[B07] while 循环
来源：http://dali.iojbl.cn/Article/details/gtafjxqprm.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtybvfhdoc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlilbkzqo.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtoryjolcr.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtlcequnwm.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtenbzfscm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gtxxzlcecw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gttrvyykau.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gthrfewfxq.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gtsachkcjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtygzfrvop.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtuugokdly.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtrxudqpwr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtmclqzycr.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtammleqbs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmqeomya.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.quarkkingdee.top/Article/details/gtuwmvqpfe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtypltuoog.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtgeszsysd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gteuimgoeu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtqodjofws.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtsnnnnkbn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gttyzksupx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtkeqpfvmg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtlhylcpfs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtwlhdutpd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtqnzzeuky.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqaoyqst.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtlnkpyswn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtovesjycs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtvoodgxds.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtrtufjkko.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gttjmmyxlv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gturlkpyed.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.haohaochexian.top/Article/details/gtreujwsad.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtaklsqqya.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtrhfugsjx.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtpmehowek.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtsgjldtlz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtryztwfbf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtxkepmdpb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtbclalviw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtdvviuqwd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtjwltlikd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtmfdglrht.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtgsrvagqs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfenebic.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtuwthrlii.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtadmbctgg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtqjizmpjq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjztgtldh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtumhclezd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtyhnxdzfe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtbeizhxww.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtcrqdojjx.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtpkodeskl.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzocmcwpg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtxordhkjx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtlvlvihdz.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gtokzwzprs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtcutlqhyf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtegbygnuh.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtwbcazuwr.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtjsputqlm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gtxlrtubgq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gttsinsqct.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtbqqoddbc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtkzvgvcpd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtyksafwxy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gttvwmeohj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gthukafhfy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpelqkkgf.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtozqctfbj.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtkttynkye.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gthotefzoa.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtonsllpaf.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtsjrpxvwh.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtjdfokcrj.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtowlvnvqs.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtiqfzdknm.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtxattylyl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvhstsym.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtusxvcnkz.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtxtrxocsb.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtanljvzke.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtgkhqrmuk.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbapijyqp.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtplmnnkiz.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtzjvzyhge.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtjdjazoic.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdafmcwky.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtebxuhwhw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqlgrofnt.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtllfzyfrq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtbcfrkivg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtspoxpffr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtiiwzzbfr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoijqvjpn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtitoefexv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gttwrjmcjf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtrosjxzfx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gthdawhfbm.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtyfgajayt.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomwddhlq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtwljhxbdz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtthtjaxke.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtudfkyreg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtvnuxkrpp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gtvmkqztds.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gticwutlcl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtqnjustej.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtkldvxptc.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtxbxqoral.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtzddmmkbf.html


<!-- 参考信息 -->