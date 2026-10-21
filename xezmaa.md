代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtlytqjrtk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtwxennwff.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gtkpzgkhnj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fengsongda.top/Article/details/gtrlxbzjec.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.wangshuangyany.cn/Article/details/gteiecatao.html

JS:   `Hello, ${name}!`
来源：http://dali.redwolf501.top/Article/details/gttrmbofek.html

TS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gtlsknwhxj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigufen.top/Article/details/gtizavcrfq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gtgkwleahc.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtqehiraxw.html

C#:   $"Hello, {name}!"
来源：http://dali.tianlin.xyz/Article/details/gtuwakqtuu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gtuwzgdtpz.html

Py:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtktwudeok.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtxxeiacdq.html

JS:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtjqgexgkv.html

TS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtcebcsrpg.html

Java: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtfhstqlcw.html

Go:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtbupagqvi.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gttvgazxoh.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gthmbucrxz.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gtkrsgcmmv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gtkaofsehu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtuvwvajjp.html

JS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtxwtlecph.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gthbxlhnfa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ehwqpu.com/Article/details/gtvdljxyxo.html

Go:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtctriznvv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hywenlv.cn/Article/details/gtiwaccrtn.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtqbzhjtzm.html

[A15] 空值判断与默认值
来源：http://dali.hnxiangtu.top/Article/details/gtrqkflbpw.html

Py:   value = data or "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtuxoxsvde.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtljmxbomn.html

JS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtnowctymi.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtshjtuxrk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.haohaochexian.top/Article/details/gticiszgod.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hfpthk.cn/Article/details/gtrmmlykkr.html

Ruby: value = data || "默认值"
来源：http://dali.zhoulong.xyz/Article/details/gtahlspwrh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbguvbab.html

[A16] 真假值判断规则
来源：http://dali.feifeiyinyue.top/Article/details/gtxuudmlld.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gtqcjyznof.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyybyrvu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyvfdevo.html

TS:   if (!x) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayqgjzpn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdmotlwu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gtftbeglna.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gtxvigwvdj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gtquhpsxnf.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gthnimpegr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtcmrzkjyd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtnibqhyks.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxvujgco.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtlgqmgofd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtlpwvjdci.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtxbfuhrvc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtrgjoegzm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtxgjnvmvh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhoulong.xyz/Article/details/gtljipyiwb.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtqakdemnr.html

PHP:  ord("A"); chr(65)
来源：http://dali.cucudq.cn/Article/details/gtzwsgilkt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtncxlnbsp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gtiphbgjmo.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenlongwang.top/Article/details/gtrxplnugx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtkomtzsnu.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gtpwrcrnhd.html

C#:   (int)'A'; (char)65
来源：http://dali.hysaishi.cn/Article/details/gtblqblric.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gtvceahkox.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gthlaixyob.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gtwxdnsngm.html

JS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gtykflnfmr.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtklkuuqpm.html

Java: int t = a; a = b; b = t;
来源：http://dali.gzhubu.top/Article/details/gtmrtpnbxb.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtylvpxppf.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtjiykxdzu.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258.top/Article/details/gtrphtwzqs.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtxyqayejk.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtmrfntmes.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjluasod.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gtobsfserl.html

TS:   // Node.js：readline 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtawizcutg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gtqyufdkfc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cdnleiting.top/Article/details/gtjhbvrqpd.html

Ruby: gets.chomp
来源：http://dali.aibaodan.cn/Article/details/gtmhqdesrx.html

C#:   Console.ReadLine();
来源：http://dali.yj20258.top/Article/details/gtfyknxndc.html

[A21] 保留指定小数位输出
来源：http://dali.zhiwuduotai.top/Article/details/gtpscnmfqb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shangyingyoupin.top/Article/details/gtzzhlhxwz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtimiiedfw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtgvnsqjfo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtsdunwogv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtzambprhh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtioznomof.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtgyhqjvoz.html

C#:   3.14159.ToString("F2")
来源：http://dali.daxiang520.top/Article/details/gtuuwokbfh.html

[A22] 获取字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtdnounpfm.html

Py:   len(s)
来源：http://dali.smart0.xyz/Article/details/gtgrlgujex.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gaohongyu789.top/Article/details/gtijprejgf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklxotkql.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtokiemheh.html

Java: s.length()
来源：http://dali.hnqzz.top/Article/details/gtimunfmxr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelrjdcnz.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gtgjlitinf.html

C#:   s.Length
来源：http://dali.316326.xyz/Article/details/gtrlidylrw.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtmlynhzjg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gteqyxybnk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnxiangtu.top/Article/details/gtybgtrjhj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtklhkrkwj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtnfbvloeu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtdkrjripj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ydzc1.top/Article/details/gtsjldifjj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258.top/Article/details/gtkpelvvsb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gtcmmhfrhh.html

[A24] 去除首尾空白
来源：http://dali.wangdashe.top/Article/details/gtabhrjaqm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gaohongyu789.top/Article/details/gttrrbzovr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ehwqpu.com/Article/details/gtabkngnuk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gtxtsugdao.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtntfofyzt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aibaodan.cn/Article/details/gtbmtqmkyo.html

Go:   strings.TrimSpace(s)
来源：http://dali.andypj.xyz/Article/details/gtrqwnyqhh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtncvltshq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtzrnylbwb.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtaoqhssjr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gtdqvldqgd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gtsftllwia.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtrjxyvpvi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtzdtkkxxd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtppwjatvu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtaagpdxvg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gtmomnrjcy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtawsgbjqn.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtoctmtlkx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtkmeabteg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqstonvx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gaohongyu789.top/Article/details/gtvtuixqrp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gtzuwiaced.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtbqezspbk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gtfnkfocln.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gtgaudplmf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtbjrsqhwd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtauvfrttd.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gtkryphjbk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfhdruqms.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gtbguineqp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtpicwzgvj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtqgyhryjr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtpckaieuk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbloaomu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtscqdugkp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtryaslmmb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gtsjgiutwh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtygsiwyip.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gttdoauxtk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gtpkzkkhpn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnnzkxkcz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtwfsjzsgv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtxmzyljiv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqcbsxab.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gtioepwxek.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gtuldiuaym.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqkucshw.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtycemslpm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gtogslfitc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtitricdre.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtwfihzrcj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtqqshmiba.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtuxkiwqjj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxtaoobx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuetiantiany.cn/Article/details/gtzknpenhj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtkqstdzfo.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtenxwfjty.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtolctxyyb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yangfankeji.com/Article/details/gthccacznt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtvbwvrgnc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtkyqgtozs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gtpmaobbld.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtcoeolmir.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gthvvscawy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtiznolbfy.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gttdbwbias.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtbigahpvq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gtbpeuwhob.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtucafezfg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtpsfvdwuh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gtgxaeiqcp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yanxiufei.cn/Article/details/gthnoyixib.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfoescmv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtajolozdx.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxutaoeu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlpzirml.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gtmknsizam.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtfnavjusz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtoaisynkr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxjzemep.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ehwqpu.com/Article/details/gtcmaqcmqb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gtsqeukhlu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtcolxenez.html

[B07] while 循环
来源：http://dali.jinghuilouyu.cn/Article/details/gttlbkuhkn.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gtznuxpjzs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtnlzgsdii.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtktdrxiuw.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtabcelvgx.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtstvbweht.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtpgyrvhfj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gtphtriwkm.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtcymorspc.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtphxslljr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtepewcnmc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtoxqzygnw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtkcdzgepb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkqkjfts.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtgmebvdhj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtrnkfoite.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sysykeji.top/Article/details/gtjnfztyaf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtjvfxmjeu.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvapnnan.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtuieyroqw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtgvivobxb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtmushckgx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtgdgqckhx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtrzfnontx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtqqtsjqeq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gtslimxndr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsnpkejtw.html

[B10] 遍历同时拿索引
来源：http://dali.xuetiantiany.cn/Article/details/gtgjemhkqm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gtjqybjjwo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gtebcejzqu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtinpptndf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtguegpvmq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzqmuwwy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gteysbizrv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtdcmwmrgz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtbkncnumr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtnowsfvwb.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtmlziktbj.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gttsnmfnhf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtecsuovzc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtbixgwghd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtjmbfrbvu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtchnokomf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtjlgucodw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtgvbjgedo.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtadctocwn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtqawmpyol.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gtkzulaviz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtrugiuopq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtitnaegaj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtzdhbouiq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtzgxksvdr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtvvvnbyzb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gttgqhrvca.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtyhpkfsws.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtojainiee.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtsjgsonig.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtkqsncabn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmjqcespe.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtfxsxtklr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gtbjveaemw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtufmrjgnd.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gthvogieuj.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gtosygtbwi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtpjirgmng.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwliuecd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtptdfmkji.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwoyjhuet.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtaevnlowm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtgkguuhnh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtgetvohev.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gteziknbjw.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtwceowxpe.html

Py:   a and b or not c
来源：http://dali.jqgfzy.top/Article/details/gtcpdnhfsp.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtoycoeydq.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtolhwyfqy.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtufoshvmh.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtxnpmyqlq.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtnsnfngmf.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtqohjxftw.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtdgrwiyfi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtqaqwindg.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtefbkiexo.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtmewokzta.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtkfrfgvad.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtnkkxlbyd.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtmyliysas.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtumrlltsd.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzpswabw.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtwtfwalcr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqosemwgr.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtfwuwxgtw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsqwlhpzr.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtbvbhyujt.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtytbmwxyl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtzzdgaylg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtkhmuvqag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtikiyludf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtbruimeot.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gtbhpydlxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtixkwdslf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtrkqwqvhs.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtdqjjorxg.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gtdlhswchf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtzcfkhdvb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtcxfzidwg.html


<!-- 参考信息 -->