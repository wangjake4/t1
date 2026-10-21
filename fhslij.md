代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymwjpttk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtsewrjcnz.html

[A12] 字符串插值 / 格式化
来源：http://dali.yangfankeji.com/Article/details/gthitefphu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gtryzirgff.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnxiangtu.top/Article/details/gtdtwveesw.html

JS:   `Hello, ${name}!`
来源：http://dali.sxryk.cn/Article/details/gttlaxddrz.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gtjzqjhfax.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gttizmijsa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sweek.top/Article/details/gtcqtchojx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhixingplan.top/Article/details/gtaczcjfnk.html

C#:   $"Hello, {name}!"
来源：http://dali.hysaishi.cn/Article/details/gtswhibvxs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sysykeji.top/Article/details/gtfbhitifo.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gttabeetvr.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtddlbasrp.html

JS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtjtcvnpnk.html

TS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtfsztoofb.html

Java: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtvilchrmu.html

Go:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtmembmexf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtmcpbvemd.html

C#:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtdvupbnwe.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gtfepzgpvj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.9152youxi.cn/Article/details/gtnsjbalvw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtjuzyoeho.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtdqhfgmqx.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gthnrzsnvr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gogol.net.cn/Article/details/gtnnmcdksy.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtdmaqdpsu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gtlsddbohu.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqvmetut.html

[A15] 空值判断与默认值
来源：http://dali.mhx1999.top/Article/details/gtdxmgwydb.html

Py:   value = data or "默认值"
来源：http://dali.tian-w.cn/Article/details/gtfpyozkgc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtnaxtuiqn.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtroaskisk.html

TS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtpjwdtsva.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtsxhqsqud.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gzhubu.top/Article/details/gtcvxnsqnt.html

Ruby: value = data || "默认值"
来源：http://dali.316326.xyz/Article/details/gtywyngxqp.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtdglivuup.html

[A16] 真假值判断规则
来源：http://dali.ppjwa.cn/Article/details/gtukeuxins.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gtmnaumjof.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ybcxt.top/Article/details/gtnjmqkecs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywxwlmaj.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgdihako.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sufxvd.cn/Article/details/gtezdqoera.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtggorvqva.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbvxhmkn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gtdxvdesdp.html

[A17] 位运算
来源：http://dali.ehwqpu.com/Article/details/gtaixzypob.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtykkjyalv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosgujrhl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtfxfcpyna.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gthrbewvrv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtzebmxsdv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtonccjjus.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfciyczf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtfrtdybql.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtlsijnhdi.html

Py:   ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtirybhrae.html

PHP:  ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtkjkwrbzi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvghrykc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtfvwztnoo.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtlmbyvkue.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gogol.net.cn/Article/details/gtinpnarqo.html

Ruby: "A".ord; 65.chr
来源：http://dali.gogol.net.cn/Article/details/gtgpzpbpzt.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxinkj.top/Article/details/gtwufxcizl.html

[A19] 交换两个变量
来源：http://dali.svipenyu.cn/Article/details/gtmugwkyrw.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtibuosowk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jianghu66.top/Article/details/gtvoiqghrw.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gtyfzzllpc.html

TS:   [a, b] = [b, a];
来源：http://dali.daria6918.cn/Article/details/gtrkqckuwl.html

Java: int t = a; a = b; b = t;
来源：http://dali.birdmap.top/Article/details/gtkbhhqqwl.html

Go:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gttuocduod.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtkamhauib.html

C#:   (a, b) = (b, a);
来源：http://dali.hywenlv.cn/Article/details/gtvspdlkdr.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gtgyhojntn.html

Py:   name = input("请输入：")
来源：http://dali.mhx1999.top/Article/details/gtqvplsnyy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gtvsoimsdh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gtlugkrvof.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gtsfjwrrin.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gtbvjknxnv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.andypj.xyz/Article/details/gtastsozuy.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtijkxvput.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtsuerutxk.html

[A21] 保留指定小数位输出
来源：http://dali.andypj.xyz/Article/details/gtjhvaeewj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gtxavidcbz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtsgypenkn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcfgfuzx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtzrmtacki.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtwhirgohi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtoyqpyboi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtwockyqhn.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbnsekndz.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtbtqjzvej.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtwwrffllz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtdywctjky.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqavzjls.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtvlmtkaik.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtcexcolxs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tanke756.top/Article/details/gtfdpxrjbq.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtcamnyjdf.html

C#:   s.Length
来源：http://dali.jqgfzy.top/Article/details/gtffdbtege.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gthzppaimw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtjnzdglpl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.svipenyu.cn/Article/details/gtquzifpej.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtiuwlngfb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gtnfjzzhzs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gttwtwgnnr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ehwqpu.com/Article/details/gtyfgwhxtc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gtkmlumzsy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gtlpvfxaoe.html

[A24] 去除首尾空白
来源：http://dali.xuanzx.com/Article/details/gthlwxbfcu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonwvlsav.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtnhhabcun.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtenstenxv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtyzfojkuk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gtusrockuw.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhlvgyeo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jianghu66.top/Article/details/gtjatzgiur.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtwzbexexo.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtgripxvdh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gteoctwyfn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xinyue.icu/Article/details/gtrbvmcnii.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtkroekbot.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtgehbciwm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvipjgygq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtonwaimvl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sysykeji.top/Article/details/gtatryaipg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtjinnpkrq.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gtpokjbbty.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gtpeaedsqi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gaohongyu789.top/Article/details/gtswqwdfxg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hysaishi.cn/Article/details/gtzxypptxo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dashuyun.cn/Article/details/gtabngqkhy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtgljocfrl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.redwolf501.top/Article/details/gtxzlbebuk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dashuyun.cn/Article/details/gtnbyykflz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtpsaqkqtv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthvajvenf.html

B. 流程控制
来源：http://dali.birdmap.top/Article/details/gtdbdkpeig.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdjhcrjfu.html

[B01] 条件判断 if / else
来源：http://dali.fzhhl.top/Article/details/gtfpvloxhp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtycipcyim.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtxpimgezm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gttzfbdlrv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gttuvvfwah.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtqckjzjpz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtrrhhviqu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtsnimxqkf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtrfsezplm.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gtafvqhgdz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuoddfyj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gtpzpqaqss.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtxrokdgyo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtnvdffwwi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtlmeqrefv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhixingplan.top/Article/details/gtevasfrjm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gtoceavxfp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtgwipztpn.html

[B03] switch / match / case
来源：http://dali.gotoacloud.top/Article/details/gtzjmlhnbc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zdqjudy.top/Article/details/gttuqbfmnl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtolnidkkg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtcwxdlyxd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtxuyctebf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtxnnnpilw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gtklvvcipp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkizmvxvt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gthscwnpqs.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtiihfslpj.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gtgtgbhjez.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gttepefqcu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtaowvtqhv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.iojbl.cn/Article/details/gtjtkxgszp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gtkxfpezoi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxctnhjb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pycfn.com/Article/details/gttqeboypk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gtfdidqotd.html

[B05] 遍历数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtzsgokgyy.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtknippfss.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gtsogcfxaa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtbemvywxs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gtbcsohwxe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gtfsphqggq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gtcelteeaq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gtcxifypms.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gtyplgctqh.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gtqitkedef.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenjidiqi.icu/Article/details/gtxszdlduw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtolhgrhfs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdwhqskv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtrwcmfmcd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtkuegdlef.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gtqwyevioo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gtoiqvauiy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hywenlv.cn/Article/details/gtqrnsmnfh.html

[B07] while 循环
来源：http://dali.c1oappe.top/Article/details/gtpnecscaw.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gtljiisjvv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtrsveiewh.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtcgzthefw.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtiutlphaq.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoybhlrfd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtkmbhyzwx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtrgtjvjgh.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtzaxgkwfc.html

[B08] do-while（至少执行一次）
来源：http://dali.jyoumei.cn/Article/details/gtqrmicfrt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqngkqfyp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gtkaanbhmg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtoroiodns.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtqmxvvdlr.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtuhucoqhf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtmowesxxz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtkaipcfzb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtvtllrujp.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtnpxshbyi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyrymzrn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtpbevmpru.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtgfzdkfge.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwhjjnjq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gthhphqhwn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtsrvhidng.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtaoobdpic.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtqlgdyube.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtecsoeybw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gtluwgqwxw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtzhwufbhn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtttakmuky.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtmwhktbui.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtwfpbqldf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gtnqjbaeou.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sufxvd.cn/Article/details/gtbxfnnhkb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtwssloekr.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtghbqiogi.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtylpxnhsz.html

PHP:  range(0, 10, 2);
来源：http://dali.meibo888.top/Article/details/gtgybtgtyl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtidsbkzhb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtpzmkdkix.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtakfonlqr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtztccxflh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtxgmmfeez.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtrrmdhlls.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gtocvrcgzx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylpmqerv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtwzjzxruy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtxbbypanl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgcnacwfu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gteckxlydv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtguxnhojy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ydzc1.top/Article/details/gtkmcuxwgc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtjnisovim.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtipptzcfq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gtnmbystjg.html

PHP:  is_numeric($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjvoxbqs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtvsaeyawj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadbcjltn.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtpbkiciuv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtffeymmop.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtabfstrtu.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gtvwftoqcg.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtwoolyefd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtggvwjqcf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtryxwjcwp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtmomslrdj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtbutwgkoi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtpzkfxqsf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtusjibxpd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvaarppn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkquhedcr.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gtnnccibrw.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtprwuhmcu.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gttwbqzqkn.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtnnlgpkfq.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcydbhsrg.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtqzpqecfh.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtfabcihwl.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbdzucqfd.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtrgpjlkog.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtxiwzhhgn.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtwkxswitd.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtrtbfqiez.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtkyzlgkse.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtxcqbjfsm.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gthsuluqik.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtcxdldrii.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtgdnifchx.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gttwuhcskd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrjjwbjql.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtnwwnzufy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxmknvibm.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtlbekftbh.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtiwmkvpxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtwrsoqiww.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtrnaatxgs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtwyvolgcq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtpsbpgkdw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtqffapscn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtgixskkcq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gteimixolw.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gteskzhryj.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtkkhzdouk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlsgfvmvx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtxkpfoomw.html


<!-- 参考信息 -->