代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtqmmcbfkm.html

Ruby: "Hello, #{name}!"
来源：http://dali.redwolf501.top/Article/details/gtugpfbeds.html

C#:   $"Hello, {name}!"
来源：http://dali.yuxming.cn/Article/details/gtwenmlrej.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yongpay.top/Article/details/gtxqiyhvqq.html

Py:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtxzfwahvz.html

PHP:  "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtyqqhruff.html

JS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtvwbzfyud.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtdjyvyzbn.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtgjrpqpgi.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtidcjodxc.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjdgqtgb.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwozoysal.html

[A14] 注释写法
来源：http://dali.hfpthk.cn/Article/details/gtqfqvzhwd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.smart0.xyz/Article/details/gtogdlrwnw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtemzlihif.html

JS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtliabxmqh.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtocwdhjls.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gtlfazwykg.html

Go:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtmlbihxsb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.0kj1m.cn/Article/details/gteijxrvou.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gttkimjvki.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gtbnbzrsum.html

Py:   value = data or "默认值"
来源：http://dali.pycfn.com/Article/details/gtimwubbpv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtcsmaqnul.html

JS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlphwiki.html

TS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtkzgtwiej.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gterdmjqbg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaonkxpwv.html

Ruby: value = data || "默认值"
来源：http://dali.xylfe.cn/Article/details/gtxjboiwux.html

C#:   var value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuanbfssi.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gtrnelkqui.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sxryk.cn/Article/details/gttvilqqrt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenjidiqi.icu/Article/details/gtebtcfphf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gzhubu.top/Article/details/gtkjdnwoow.html

TS:   if (!x) {}
来源：http://dali.ehwqpu.com/Article/details/gtcwzccsml.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtttzknzad.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yvedp.cn/Article/details/gtizlwghcn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.iojbl.cn/Article/details/gtqukzhcii.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.0kj1m.cn/Article/details/gttmaoodnv.html

[A17] 位运算
来源：http://dali.nanxinkj.top/Article/details/gtxdikqnmr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvheabtp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtrzcqlhjj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtzfcbmths.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfaukjjs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtrpiqiigp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtjrwfticq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtvdllysfx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtahkicrkm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.quarkkingdee.top/Article/details/gtifvyzalq.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtulcebicd.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtrohcgvcx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtawpfdsth.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gtpvquzoao.html

Java: (int) 'A'; (char) 65
来源：http://dali.yuanzhike.top/Article/details/gtnehklxwo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gtyukpeoji.html

Ruby: "A".ord; 65.chr
来源：http://dali.dianchejie.cn/Article/details/gtuibrfnvp.html

C#:   (int)'A'; (char)65
来源：http://dali.cheryme.top/Article/details/gtmjpjdong.html

[A19] 交换两个变量
来源：http://dali.hammf.cn/Article/details/gtfkgywbnx.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtmejrkkrj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sxryk.cn/Article/details/gtlonhrinb.html

JS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gtghtgzkze.html

TS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtntgcdzfd.html

Java: int t = a; a = b; b = t;
来源：http://dali.snrcjt.cn/Article/details/gtiklngtie.html

Go:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gteiqzemcz.html

Ruby: a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gtpsxkvjdv.html

C#:   (a, b) = (b, a);
来源：http://dali.sysykeji.top/Article/details/gtsazhdwyu.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gtqsqiomna.html

Py:   name = input("请输入：")
来源：http://dali.gotoacloud.top/Article/details/gtijkhgjjy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gtmlycicvy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtuxhgavnu.html

TS:   // Node.js：readline 模块
来源：http://dali.cheryme.top/Article/details/gterajdiyi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.svipenyu.cn/Article/details/gtyceiocgo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yanxiufei.cn/Article/details/gtqvodysaq.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gtucbwmsco.html

C#:   Console.ReadLine();
来源：http://dali.hysaishi.cn/Article/details/gthxotzbtk.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gtndpaksem.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenlongwang.top/Article/details/gtlvlivnxr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gtogmudtca.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtkqttfrlq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gttonevsxl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtwhutgqbn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtjphlbxic.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtujxidwni.html

C#:   3.14159.ToString("F2")
来源：http://dali.ivvv.top/Article/details/gtzeocyjke.html

[A22] 获取字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtutcofggk.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtpwseobuw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuxming.cn/Article/details/gtuayceeje.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj202588.top/Article/details/gtnpmshmgc.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gtyzhgfubj.html

Java: s.length()
来源：http://dali.chenzaomai.com/Article/details/gtipgwjohb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gtkibkekep.html

Ruby: s.length
来源：http://dali.ybcxt.top/Article/details/gtgcramtek.html

C#:   s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzlclsut.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtrvrdnrun.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj202588.top/Article/details/gtsvmjunhl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.bjfxy.top/Article/details/gtukzbnlus.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwuajlsi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtbcrthold.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtwwfekdpd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ydzc1.top/Article/details/gtrfqgebwj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtbpblrnym.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yvedp.cn/Article/details/gtesljzsgf.html

[A24] 去除首尾空白
来源：http://dali.sysykeji.top/Article/details/gtvgqdgjob.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tianlin.xyz/Article/details/gtgzxlgtwb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gtvuzblppe.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gtdjzilmcd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gtbtszapri.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gtslrdttfg.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gtgutgqxzf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jyoumei.cn/Article/details/gtfafsufxv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtziaeevbc.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gteczmhloa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gtaziilmph.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtpirmbeik.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtvcxjygjj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtobjcbzqt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ybcxt.top/Article/details/gtvklakbqy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtiqsdumnv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtmxekwjil.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtvgjpurhl.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnjedypg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhengqikj.top/Article/details/gthoillfav.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gtgqrsdwhz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pengpengdd.cyou/Article/details/gtdfvrkwwr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtgbxbevcs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjprsndrf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gtuitcadpr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gttwaauljq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtgwyhijei.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnodcxqdi.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gtmwcuylio.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfpbfnwni.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gtdrtbaann.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtrthqbxzw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gtzdqlmpru.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtybyipjla.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtlubgwyvf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtgqshsham.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gtfqvplrjv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gtwngmpiub.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtyblphcfq.html

[B02] 多分支 else if / elif
来源：http://dali.pycfn.com/Article/details/gtfqkwplvo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gtwrvnmfej.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyqxkipon.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtalvalovx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtscztwhfd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gttrblsjrv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdtgyxus.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gtexyqfhck.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtmrdffjpu.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gtbtzanrye.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yonumen.top/Article/details/gtzmvrwxpz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtjcvodevr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtzzwvmsem.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtrgdhaeyv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtvoswrzgx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtyzwbxphg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gtvlhnnfdv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gttrqojxwf.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtlukbbpus.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gtmisfxany.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtqgwxgxtv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtmugdmbfm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtplpnqytp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.haohaochexian.top/Article/details/gthzmlbuxm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sxryk.cn/Article/details/gtldzyzsmi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gthcvqikzv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.316326.xyz/Article/details/gtbyntmlty.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtvwjivmri.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gtduukjwcj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gtbcdkexqr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthotkcmp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gteptmlpde.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpnxudbsy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gtvqqrzczf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtzrygfzaf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gteagvgbmg.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtudsnuhkk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcrbjpfn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.birdmap.top/Article/details/gtivouumvp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gtlrqeamhl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbfscfgym.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gtqgdvpocf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtcbikjcbz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtofyrawms.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtakjkmvrv.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtdspqqhbx.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtpligadsr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gteldrpbod.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtyvmiwmqm.html

TS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtqbtjidnp.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtknsymimc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gtzlbjeval.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gtyqaabkdq.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtugnikzzz.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gtefeaqvfz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtkqjeheai.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtgfuitwqk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtrnftakse.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtalwzcfpa.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtnkhpcbjl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtyxiesaft.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gtiucurkze.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtiufxsecb.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gtgyptjvdb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gtuvwxcmfy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtgsphjoop.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtdmmrpjwd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtvbjoohgc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtkznxaype.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtkllhdmwb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.meibo888.top/Article/details/gtkkhxmbck.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtxjckzsjn.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtmhkzmjjy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gthpvusssw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtnpjhfjgr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtdjdprrda.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtzliclxtd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtfpeeeoim.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtbiporwfv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gtjsclleud.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtlhonosqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gtezmaiymb.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtrpqcyqey.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtqzppisil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtkyuqadvu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtacxavqem.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtwpoajxel.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gtzvltomns.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtpnmlnvom.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuanzx.com/Article/details/gtazndikvf.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtxxcqavxs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtfotlehpj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gtwuibmwro.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwyhcxyd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtpwnjasnm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtjiilcyrm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtradvgbln.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtygaznmdr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtvdcnkngu.html

[B13] 判断是否为数字
来源：http://dali.xylfe.cn/Article/details/gtxmicfzdi.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtlyuzssov.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gtzckelzlg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtrzwwsfly.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gteihlzdgf.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtxdsdfbwd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtazcgaspz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtagwuceqv.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gtqvrglddp.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtbrnlpbim.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtxapmgxki.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtkvkvqpst.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtgroblzqr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtavdzumxz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtybxqhkfi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtizpppspz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gthinfiqeo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtjitkfbxv.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gttdeafrcd.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtukfzrimo.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gtwpzasleh.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtpncemenu.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtegjwyayw.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtyeffkkzj.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtiiyywlzl.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtcfghidkw.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gthivflylk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtfalpryca.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gteyttlukp.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtgbmrtobn.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtvqetizxv.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtwastoqao.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtbeindyxq.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtcdglifgc.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtzorrrqbc.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtcrthptss.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvqaouqqq.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtsueridqn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsjpbssou.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtyyuvwzli.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtcrpxjbta.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtakebynlf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtltwixsaz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvjzyady.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvrpdltm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtrgesldxz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtwkqypnmo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtyrndpcml.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtpzgtywgm.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtvkwefjaq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpghmfnlb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtmvvqbvcj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpteukgmg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gttsgaflez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtzffnptee.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtonpewest.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gtdotyevob.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtiguzgnjw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtynejeegw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtvhlzwpnw.html


<!-- 参考信息 -->